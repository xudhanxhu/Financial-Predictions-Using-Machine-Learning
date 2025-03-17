# 📈 Financial Prediction - Machine Learning & Deep Learning

## 📌 Overview
The **financial prediction model** designed to accurately forecast cryptocurrency prices using a combination of **LSTM networks, Attention Mechanisms, and Convolutional Layers**. Built with **TensorFlow/Keras**, it leverages **feature engineering, hyperparameter tuning, and predictive uncertainty estimation** to provide robust and reliable predictions.

## 📊 Dataset
- **Source:** Yahoo Finance via `yfinance` API.  
- **Data:** Historical cryptocurrency prices, including Open, High, Low, Close, Volume.  
- **Features Engineered:** Moving Averages (MA), RSI, MACD, Bollinger Bands, OBV, Volatility, etc.  
- **Target:** Close Price prediction.

## 🧩 Key Features
✅ **Advanced Deep Learning Architecture:** Bidirectional LSTM with Attention Mechanism for improved sequence learning.  
✅ **Feature Engineering:** Multiple technical indicators (MA, RSI, MACD, etc.) added to enhance prediction accuracy.  
✅ **Monte Carlo Dropout:** Uncertainty estimation using multiple forward passes.  
✅ **Hyperparameter Tuning:** Optimized using **Optuna** for the best model performance.  
✅ **Future Price Prediction:** Robust forecasting over multiple days with confidence intervals.  
✅ **Visualization:** Interactive plotting of predictions and confidence intervals.

## 📌 Model Performance
| Metric               | Value           |
|--------------------- |-----------------|
| Mean Squared Error (MSE)    | 18242.13          |
| Root Mean Squared Error (RMSE)| 135.06         |
| Mean Absolute Error (MAE)    | 102.22          |
| R² Score                     | 0.9278         |
| Directional Accuracy         | 60.33%        |

## 📢 Results & Insights
- The model demonstrates **Decent accuracy** in predicting cryptocurrency price trends.  
- **Attention Mechanism** enhances interpretability by identifying important time steps.  
- **Monte Carlo Dropout** provides valuable insights into model confidence.  
- The model captures both short-term fluctuations and long-term trends effectively.