# Exploratory Data Analysis (EDA) and essay
## Introduction

This assignment focuses on one of the most important aspects of data science, Exploratory Data Analysis (EDA). Many surveys show that data scientists spend 60-80% of their time on data preparation. EDA allows you to identify data gaps & data imbalances, improve data quality, create better features and gain a deep understanding of your data before doing model training - and that ultimately helps train better models. In machine learning, there is a saying - "better data beats better algorithms" - meaning that it is more productive to spend time improving data quality than improving the code to train the model.

This will be an exploratory exercise, so feel free to show errors and warnings that arise during the analysis.

## Dataset

A Portuguese bank conducted a marketing campaign (phone calls) to predict if a client will subscribe to a term deposit  The records of their efforts are available in the form of a dataset. The objective here is to apply machine learning techniques to analyze the dataset and figure out most effective tactics that will help the bank in next campaign to persuade more customers to subscribe to the bank's term deposit. Download the Bank Marketing Dataset from: https://archive.ics.uci.edu/dataset/222/bank+marketing

## Assignment

1. Exploratory Data Analysis
Review the structure and content of the data and answer questions such as:
   * Are the features (columns) of your data correlated?
   * What is the overall distribution of each variable?
   * Are there any outliers present?
   * What are the relationships between different variables?
   * How are categorical variables distributed?
   * Do any patterns or trends emerge in the data?
   * What is the central tendency and spread of each variable?
   * Are there any missing values and how significant are they? 
  
2. Algorithm Selection
Now you have completed the EDA, what Algorithms would suit the business purpose for the dataset. Answer questions such as:
   * Select two or more machine learning algorithms presented so far that could be used to train a model
(no need to train models - I am only looking for your recommendations).
   * What are the pros and cons of each algorithm you selected?
   * Which algorithm would you recommend, and why?
   * Are there labels in your data? Did that impact your choice of algorithm?
   * How does your choice of algorithm relates to the dataset?
   * Would your choice of algorithm change if there were fewer than 1,000 data records, and why? 

3. Pre-processing
Now you have done an EDA and selected an Algorithm, what pre-processing (if any) would you require for:
   * Data Cleaning - improve data quality, address missing data, etc.
   * Dimensionality Reduction - remove correlated/redundant data than will slow down training
   * Feature Engineering - use of business knowledge to create new features
   * Sampling Data - using sampling to resize datasets
   * Data Transformation - regularization, normalization, handling categorical variables
   * Imbalanced Data - reducing the imbalance between classes

## Deliverable

**Essay** (minimum 500 words)
Write a short essay summarizing your findings. Explain your selection of algorithms and how they relate to the data and what you are trying to do.
Format: PDF

**Code**
This should include your code, as well as the outputs of your code e.g. correlation chart
Format: Code should be saved in https://rpubs.com or https://github.com. Please provide a link to your code repo in the submission. Please do not submit your code via Google Colab (due to permissioning issues).

Q&A:

Python or R
Previously this course used only R (as most of your prerequisite courses used R). Due to student demand the course has been extended to cover Python - so you can use the Python textbook and do the assignments in Python. 
Working individually vs groups
Assignments should be submitted individually so credit can be assigned to person doing the work. Any work you copy or leverage should be attributed e.g. from the internet or from another student.
RPub and Github accounts
Please register for an account if you don't already have one (accounts are free).
Google Colab
I don't accept Google Colab. 80% of the time Google Colab hasn't been set up to give me permissions to view the code. I cannot grade work I don't have access to.
Rubric

| Activity                        | Points | Requirements                                                                                                                                                                                                                                                                                                                                                 |
|----------------------------------|--------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Exploratory Data Analysis (EDA)** | 20     | 1. Features (columns) correlation, graph & insights drawn (2)<br>2. Relationship between variables (domain knowledge, e.g., combining features) (2)<br>3. Feature distribution & insights drawn (2)<br>4. Outliers detected; impact and recommendations for handling (2)<br>5. Categorical variables (2)<br>6. Patterns/trends in data, and insights drawn (2)<br>7. Central tendency & spread of variables (2)<br>8. Missing values & significance (2)<br>9. Duplicate or inconsistent values identified (2)<br>10. Does the data align with domain knowledge & expectations (2) |
| **Algorithm Selection**          | 20     | Justification for selection of algorithm (model) based on:<br>1. Data characteristics, constraints & insight (10)<br>2. Problem Type (Supervised vs. Unsupervised) (5)<br>3. Business insight (interpretability vs accuracy, data availability, speed, scaling, etc.) (5)<br>&nbsp;&nbsp;&nbsp;&nbsp;- Think about business goals and how you are working towards them |
| **Pre-processing**               | 20     | 1. Data quality & completeness (5)<br>&nbsp;&nbsp;&nbsp;&nbsp;- addressing missing data<br>&nbsp;&nbsp;&nbsp;&nbsp;- including handling of outliers & noise<br>2. Feature distribution & scaling (5)<br>&nbsp;&nbsp;&nbsp;&nbsp;- features were normalized/standardized<br>&nbsp;&nbsp;&nbsp;&nbsp;- ensure data distribution aligns with model<br>3. Feature Selection (5)<br>&nbsp;&nbsp;&nbsp;&nbsp;- appropriate features selected for predictive power<br>&nbsp;&nbsp;&nbsp;&nbsp;- handling of categorical variables<br>&nbsp;&nbsp;&nbsp;&nbsp;- creation of synthetic variables (optional)<br>4. Domain knowledge & business context (5)<br>&nbsp;&nbsp;&nbsp;&nbsp;- incorporate business & data insights<br>&nbsp;&nbsp;&nbsp;&nbsp;- ensure features align with real-world and make sense |
| **Code**                        | 20     | 1. Code provided (5)<br>2. Code quality & completeness (5)<br>3. Comments & explanation provided (5)<br>4. Outputs included (5)                                                                                                                                                                                                                              |
| **Essay**                       | 20     | 1. Exploratory data analysis (5)<br>&nbsp;&nbsp;&nbsp;&nbsp;- Summarize findings & issues<br>&nbsp;&nbsp;&nbsp;&nbsp;- Conclusions drawn about data<br>2. Algorithm selection (5)<br>&nbsp;&nbsp;&nbsp;&nbsp;- Selection of algorithm is justified & consistent with EDA<br>3. Pre-processing (5)<br>&nbsp;&nbsp;&nbsp;&nbsp;- Issues identified in EDA were addressed<br>&nbsp;&nbsp;&nbsp;&nbsp;- Changes specific to algorithm were identified & addressed<br>4. Business insight & recommendations (5)<br>&nbsp;&nbsp;&nbsp;&nbsp;- Conclusions were reached & justified by actual results/metrics |
| **Total**                       | 100    |                                                                                                                                                                                                                                                                                                                                                              |
