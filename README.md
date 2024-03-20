# Polars-package-OIM7502-Midterm
This is for Babson College OIM7502's midterm project in Spring 2024. 

I will introduce the Python Polars package in this repository with the following materials:
1. slide deck
2. tutorial("Demonstration" file)
3. code examples
## Polars Overview
Polars is a DataFrame library to manipulate structured data. It is available for Python, R and NodeJS. 

According to Polars' official website (https://docs.pola.rs/), its key features are:
1. Fast: Written from scratch in Rust, designed close to the machine and without external dependencies.
2. I/O: First class support for all common data storage layers: local, cloud storage & databases.
3. Intuitive API: Write your queries the way they were intended. Polars, internally, will determine the most efficient way to execute using its query optimizer.
4. Out of Core: The streaming API allows you to process your results without requiring all your data to be in memory at the same time
5. Parallel: Utilises the power of your machine by dividing the workload among the available CPU cores without any additional configuration.
6. Vectorized Query Engine: Using Apache Arrow, a columnar data format, to process your queries in a vectorized manner and SIMD to optimize CPU usage.

Polars support a wide range of data formats, including text, binary, IPC, databases, and cloud storage. With such wide range of data formats, users can more conveniently integrate Polars with their existing data stack. 
## Installation Instructions
To install Polars in Python, simply enter the following code:

`pip install polars`

To use the Polars after installation, simply import it by entering the following code:

`import polars as pl`

The above method can successully install the core function of Polars onto Python. To install the optional dependencies like pandas or numpy, enter the following code:

`pip install 'polars[dependency name 1, dependency name 2]'`

For a complete list of dependencies, please check Polars' official website at https://docs.pola.rs/user-guide/installation/
