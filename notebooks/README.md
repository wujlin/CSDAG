# CSDAG
This repository contains the code and data for the paper *"Dynamic Interplay Between Public Sentiment Well-being and Information Flows in Long-COVID Discourse"*.
All models are deployed on a remote server, with 2 RTX4090 GPUS. 

- **ABM**: Implements the agent-based model (ABM) used in the paper, detailing the computational processes outlined in the manuscript.
- **Text_mining**: Contains code for text processing and sentiment analysis.
- **Prediction**: Includes the training and prediction code for modeling the transitions in node states.
- **Empirical study**: 对经验数据进行挖掘和分析
- **


### Key Figures:

1. **CSDAG Framework**  
   Our proposed framework for health communication models various groups of agents on multi-layer networks.  
   ![CSDAG Framework](./Graph/CSDAG.png)

2. **Network Evolution**  
   The simulation results show the evolution of node states over time.  
   ![Network Evolution](./Graph/network_evolution.png)

3. **Model Performance**  
   The method effectively captures the temporal dynamics of node states.  
   - Sentiment and metric trends:  
     ![Metric and Sentiment Trends](./Graph/metric+sentiment_lines.png)
   - Media metrics and risk assessment:  
     ![Media Metric and Risk Trends](./Graph/media_metric_risk_lines.png)
   - Parameter distribution with mean and 3SE bars:  
     ![Parameter Distribution](./Graph/parameter_distribution_with_mean_and_3se_bars.png)
   - Fine-tuned accuracy for three tasks:
     ![Accuracy](./Graph/model_accuracy.png)
   - Overview of Research Methodology:
     ![Methodology](./Graph/framework.png)    
