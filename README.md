🏠 Pakistani Housing Price Prediction

This project focuses on predicting real estate housing prices in Pakistan using machine learning models. The goal is to analyze key property features such as location, city, area size, number of bedrooms, and bathrooms, and then build predictive models to estimate property prices with high accuracy.

📊 Dataset:
The dataset includes real estate listings with the following important columns:
City, Location, Province
Area Size, Area Type, Area Category
Bedrooms, Baths
Purpose (Sale / Rent)
Price (Target variable)

⚙️ Approach:
Data Preprocessing
Handling missing values
Encoding categorical features (Label Encoding)
Log-transform applied on skewed features (e.g., Price)

Modeling:
Random Forest Regressor (improved performance)
Cross-validation for model robustness
Evaluation Metrics
R² Score (Coefficient of Determination)
MAE (Mean Absolute Error)
MSE (Mean Squared Error)

📈 Results:
Random Forest Regressor
R² Score: 0.99
MAE: 4,205
MSE: 5.02e+10
✅ Random Forest performed significantly better and provided highly accurate predictions.

🔍 Visualization:
The graph below shows Actual vs Predicted Prices.
The red dashed line represents the perfect prediction line.
Blue points are the predicted values.
The closer they are to the red line, the better the model performance.

🚀 Future Work:
Hyperparameter tuning with GridSearchCV
Try Gradient Boosting and XGBoost models
Deploy the model with Streamlit or Flask for real-world usage

👨‍💻 Author:
Developed by Zain
Data Scientist | Machine Learning Enthusiast
