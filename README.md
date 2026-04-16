# Insurance Claim Amount Prediction

## Objective

The objective of this project is to estimate medical insurance claim amounts based on personal attributes such as age, BMI, smoking status, and other demographic factors.

## Approach

* Loaded and explored the Medical Cost Personal dataset
* Preprocessed data by encoding categorical variables (sex, smoker, region)
* Split the dataset into training and testing sets
* Trained a Linear Regression model to predict insurance charges
* Visualized relationships between BMI, age, smoking status, and charges
* Evaluated model performance using MAE and RMSE

## Results and Insights

* The Linear Regression model achieved:

  * MAE: **4186.51**
  * RMSE: **5799.59**
* Smoking status has the strongest impact on insurance charges
* Age shows a strong positive relationship with medical expenses
* BMI also affects charges but less significantly compared to smoking
* The model performs reasonably well but could be improved using advanced models like Random Forest or XGBoost
# insurance-claim-prediction
