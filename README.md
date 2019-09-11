# Artificial Neural Network Model to Predict Employee Retention Using Keras with TensorFlow.
This project is guided and inspired by [Steve Nouri](https://www.linkedin.com/in/stevenouri/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
Retaining the best employees is an important factor for most organizations.
In this tutorial, we will build a deep learning model that will predict the probability of an employee leaving a company.
We will use the Keras sequential layer to build the different layers for the model.

`Predictors:`
```
satisfaction_level
last_evaluation
number_project
average_montly_hours
time_spend_company
Work_accident
promotion_last_5years
department
salary
```

`Target:`
```
left (0: Stay, 1: Left)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting.

### Instructions
1. Downloaded the [dataset](https://github.com/zhenyu92/Deep_Learning_Employee_Retention/blob/master/HR_comma_sep.csv) or from [Kaggle](https://www.kaggle.com/liujiaqi/hr-comma-sepcsv).
2. Run and execute the [IPython](https://github.com/zhenyu92/Deep_Learning_Employee_Retention/blob/master/Deep%20Learning%20on%20Employee%20Retention%20Prediction.ipynb).
    The following items will be covered and explained, and eventually derive a model with best prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
      3.1 Handling Categorical Variables
    4 Train Test Split
      4.1 Data Scaling
    5 Building ANN
      5.1 Gradient Descent
    6 Select and Train a Model
    7 Apply Model on Test Set
      7.1 Evaluate Model on Confusion Matrix
    8 Improving the Model
      8.1 Applying Cross Validation
      8.2 Adding Dropout Regularization
      8.3 Applying Grid Search
    ```   
    
### Conclusion
We have demonstated how to used `Keras` to build an artificial neural network that predicts the probability that an employee will leave a company. 
To further improve the model, we tried different activation functions or optimizer functions from Keras.
We also used `GridSearch` to figure out the `best parameters` for the classifier. 
The employee retention model we built is able to predict if an employee stays or leaves with an accuracy of up to `86%`.
