# SE305 Homework Lab2 ---- hotel
#### Group members: 
>  **Wenzhu Luo, Wenjie Wu, Xuejia Chen, Chenyu Lan**

The project is based on Django 1.4+

## Installation
> Pre-condition: Make sure you have Django 1.4+ environment.

1. Create database `hotel` in MySQL


    `[mysql] create database hotel;`


2. Sync Django Model with MySQLdb


    `[shell]$ python manage.py syncdb`

3. Insert some test data into database.


     `[mysql] source insertdata.sql;`
