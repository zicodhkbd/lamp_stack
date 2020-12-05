#!/bin/sh
# Install Apache to check from web browser using 0.0.0.0 or localhost, check version, start,stop & restart Apache into Ubuntu
sudo apt update
sudo apt upgrade
sudo apt install apache2 all
apache2 -v
sudo service apache2 start
sudo service apache2 stop
sudo service apache2 start
sudo service apache2 restart 
# Visit:  http://localhost/


# Install MySQL & check version, start,stop & restart Apache
sudo apt-get mysql
mysql --version
sudo service mysql start
sudo service mysql restart


# Create MySQL DB, User
sudo mysql -u root -p
CREATE DATABASE masum DEFAULT CHARACTER SET utf8 COLLATE utf8_unicode_ci;
GRANT ALL ON alam.* TO 'alamgir'@'localhost' IDENTIFIED BY '@lam&!r';
use alamgir;
EXIT;

# Install PHP & check version 
sudo apt install php7.2-fpm php7.2-common php7.2-mbstring php7.2-xmlrpc php7.2-soap php7.2-mysql php7.2-cli php7.2-zip php7.2-curl
php --version
locate php
whereis php


# Install PHPmyAdmin
sudo apt update 
sudo apt install phpmyadmin 

sudo service apache2 restart 
# visit: http://localhost/phpmyadmin/
Use user= trainee 
pass= S@Ssion786@
For login Phpmyadmin
