# Fraud Detection
## This project focuses on developing and evaluating machine learning models for credit card fraud detection, with a comparative analysis between the XGBoost, CatBoost and Random Forest classification algorithms. The objective is to identify the most effective model for accurately detecting fraudulent transactions while minimizing false positives, thereby improving the reliability and efficiency of fraud prevention systems in financial institutions.

## Insights Summary
#### The models were trained and optimized through hyperparameter tuning to enhance detection accuracy and computational efficiency. Among the models tested, CatBoost demonstrated the best overall performance, achieving the highest recall and slightly faster prediction time than XGBoost. This suggests that CatBoost was marginally more effective in identifying fraudulent transactions, which is critical in minimizing financial losses and false negatives. However, the improvement over XGBoost was modest.

#### XGBoost, on the other hand, exhibited significantly faster training time, making it a more computationally efficient choice for large-scale or frequently updated datasets. While its recall was marginally lower than CatBoost, its overall trade-off between speed and performance remains attractive for production environments where retraining speed is essential.

#### In contrast, Random Forest underperformed across all key metrics, showing lower recall and longer prediction times, making it less suitable for real-time fraud detection scenarios.

#### In summary, while both CatBoost and XGBoost performed strongly, CatBoost was the top performer in detection accuracy and prediction efficiency, whereas XGBoost remains the more practical choice for faster model updates. The results highlight that CatBoost may be preferred for accuracy-critical applications, while XGBoost may suit time-sensitive or resource-constrained systems. Future enhancements include integrating real-time detection pipelines, model retraining on new data, and exploring ensemble methods to combine the strengths of both models.
