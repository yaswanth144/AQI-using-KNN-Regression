# KNN-Regression
# About the dataset and objective:
The dataset AQI.csv contains 1093 rows and 9 columns.Our objective is to find Air Quality Index.

# Procedure
Load required libraries.

Load dataset and remove null values.

Visualize the columns with seaborn's pairplot.

## Correlation Matrix with Heatmap.

Correlation states how the features are related to each other or the target variable.

Correlation can be positive (increase in one value of feature increases the value of the target variable) or negative (increase in one value of feature decreases the value of the target variable)

Heatmap makes it easy to identify which features are most related to the target variable.

## Feature Importances

You can get the feature importance of each feature of your dataset by using the feature importance property of the model.

Feature importance gives you a score for each feature of your data, the higher the score more important or relevant is the feature towards your output variable.

Feature importance is an inbuilt class that comes with Tree Based Regressor, we will be using Extra Tree Regressor for extracting the top 10 features for the dataset.

## Training the model
Divide the dataset into train and test data using train_test_split.

Now create a knn regression model(k=1) and fit (x_train,y_train).

predict the x_test and calculate losses.

Do hyperparameter tuning on k value and visualize accuracy.

predict the x_test and calculate losses for accurate k-value.

## NOTE: 
losses can be

## MAE:
MAE is the easiest to understand, because it's the average error.

## MSE : 
MSE is more popular than MAE, because MSE "punishes" larger errors, which tends to be useful in the real world.

## RMSE: 
RMSE is even more popular than MSE, because RMSE is interpretable in the "y" units.
