# Practical Machine Learning Course Project
------------

This is about Coursera Data Science Module 8 - Practical Machine Learning Course Project

## Background
------------

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).

## Data
------------
The training data for this project are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv


## Machine Learning Model
------------

The PracticalMachineLearning.Rmd does the following:

Load both training and testing datasets and remove any NA rows.

Filter the training and testing datasets to only keep columns which has significant predicting influencial factor.

Split the training data into 7:3 ratio for training and validation purpose.

Develop Random Forests Prediction Algoritm and evaluate that the prediction accuracy is high.

Apply the Random Forests model to the testing data and print out the result with 'problem_id_x.txt'


## HTML Report
------------

The PracticalMachineLearning.html is also uploaded as index.html in the gh-pages branch.

You can view the HTML report [here](https://wweiw.github.io/PracticalMachineLearning/)


## Branches and Format
------------
The R markdown file (Rmd) is in the **master** branch.
The HTML file is in the **gh-pages** branch.