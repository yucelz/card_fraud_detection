# card_fraud_detection Event classification for payment card fraud detection

## Introduction
Payment fraud detection is critical for banks, businesses, and consumers. In Europe alone, fraudulent transactions were estimated at €1.89 billion in 2019. Worldwide, approximately 3.6% of commerce revenue is lost to fraud. In this notebook, we train and evaluate a model to detect fraudulent transactions using the synthetic dataset attached to the book Reproducible Machine Learning for Credit Card Fraud Detection by Le Borgne et al.

Fraudulent transactions often cannot be detected by looking at transactions in isolation. Instead, fraudulent transactions are detected by looking at patterns across multiple transactions from the same user, to the same merchant, or with other types of relationships. To express these relationships in a way that is understandable by a machine learning model, and to augment features with feature engineering, we We use the Temporian preprocessing library.

We preprocess a transaction dataset into a tabular dataset and use a feed-forward neural network to learn the patterns of fraud and make predictions.