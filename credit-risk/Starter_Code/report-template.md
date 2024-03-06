# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

* The purpose of the analysis is to identify the creditworthiness of borrowers. The financial information the data is located on a csv file that is composed of lending data. The "y" variable is set equal to the loan status. The value counts variable counts the distinct values of the resampled labels data. The machine learning process is composed of fitting a logistic regression model by training the data. Then the predictions are saved for the testing data by using the esting feature data and the fitted model. A confustion matrix and classifcation report is made to evaluate the models performance. Logistic regression is a binary outcome predictior that predicts the probability of a binary outcome. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Accuracy is 0.99. 
  * Precision for 0 is 1.00, for 1 is 0.87. 
  * Recall for 0 is 1.00, for 1 is 0.89. 


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Accuracy is 0.99. 
  * Precision is 0.99. 
  * Recall is 0.99. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
* I recommend the logistic regression model fit with the oversampled data due to its accuracy, precision, and recall scores. 
