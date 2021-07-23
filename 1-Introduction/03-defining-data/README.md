# Defining Data

## Introduction
Data are facts, information, observations and measurements that are used to make discoveries and to support informed decisions. A dataset, which is a collection of data may come in different formats and structures, and will usually be based on its source, or where the data came from. For example, a company's monthly earnings might be in a spreadsheet but hourly heart rate data from a smartwatch may be in [JSON](https://stackoverflow.com/a/383699) format. It's common for data scientists to work with different types of data within a dataset. 


This lesson focuses on identifying and classifying data by its characteristics and its sources.

## Pre-Lecture Quiz

[Pre-lecture quiz]()


## How Data is Described

### Raw Data
### Numerical
### Categorical


## How Data is Structured

## Structured Data
Structured data is data that is organized into rows and columns, where each row will have the same set of columns. Columns represent a value of a particular type and will be identified with a name describing what the value represents, while rows contain the actual values. Columns will often have a specific set of rules or restrictions on the values, to ensure that the values accurately represent the column. For example imagine a spreadsheet of customers where each row must have a phone number and the phone numbers never contain alphabetical characters. There may be rules applied on the phone number column to make sure it's never empty and only contains numbers. 

A benefit of structured data is that it can be organized in such a way that it can be related to other structured data. However, because the data is designed to be organized in a specific way, making changes to its overall structure can take a lot of effort to do. For example, adding an email column to the customer spreadsheet that cannot be empty means you'll need figure out how you'll add these values to the existing rows of customers in the dataset. 

Examples of structured data: spreadsheets, relational databases, phone numbers, bank statements

![image of type]()
*type description*

## Unstructured Data
Unstructured data typically cannot be categorized into into rows or columns and doesn't contain a format or set of rules to follow. There are tools and methods to convert an unstructured dataset into a structured format, but could turn into a tedious task. Because unstructured data has less restrictions on its structure it's easier to add new information in comparison to a structured dataset. If a sensor capturing data on barometric pressure every 2 minutes has received an update that measures and records temperature, it doesn't require altering the existing data. However, this may make analyzing or investigating this type of data take longer. For example, a scientist who wants to find the average temperature of the previous month from the sensors data, but discovers that the sensor recorded an "e" in some of its recorded  to note that it was broken instead of a typical number, which means the data is incomplete.

Examples of unstructured data:  text files, social media comments, text messages, video files

![image of type]()
*type description*

## Semi-structured


## Sources of Data
### Internet
#### APIs
#### Scraping
### Spreadsheets


## 🚀 Challenge


## Post-Lecture Quiz

[Post-lecture quiz]()

## Review & Self Study


## Assignment

[Assignment Title](assignment.md)