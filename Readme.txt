Scalable Cloud Programming

This project demonstrates how to use PySpark within a Jupyter notebook to perform data processing and analysis.

Table of Contents
Introduction
Prerequisites
Installation
Usage
References

1. Introduction

The following project is a demonstration of the use of PySpark and related Jupyter notebooks for big data management. PySpark is a processing interface of Apache Spark that uses Python language, Apache Spark is an open source, fast and lightweight cluster computing system.

2. Prerequisites
Before you can run the notebook, ensure you have the following installed:

Ubuntu
Python 3.x
Jupyter Notebook
Apache Spark
PySpark

3. Installations
Download the latest version of Spark. To download Spark, run the following command in the terminal.
-> curl -O https://dlcdn.apache.org/spark/spark-3.5.1/spark-3.5.1-bin-hadoop3.tgz

Unpack the archive file and remove the zip file
->sudo tar -xzf ~/spark-3.5.1-bin-hadoop3.tgz
->rm ~/spark-3.5.1-bin-hadoop3.tgz

Install the latest version of Python
-> sudo apt install python3

Install Jupyter Notebook
-> sudo pip3 install notebook

4. Usage
Inside the Jupyter Notebook, certain computations are done on the dataset to extract the results as requested. The notebook contains the code cells such as:
a. Initializing a Spark session and importing all the dependencies.
b. Loading the dataset to the DataFrame
c. Performing data transformations and actions
d. Printing the outputs.

5. References
https://spark.apache.org/documentation.html
https://spark.apache.org/docs/latest/api/python/
https://docs.jupyter.org/en/latest/