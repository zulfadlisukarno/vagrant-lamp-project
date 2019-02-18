# vagrant-lamp-project

This is a skeleton repository where you can clone and get your development environment ready. You'll only need vagrant to be installed.

What will Vagrantfile provide:
 - Ubuntu 16.04
 - Latest PHP 7 from onrej PPA
 - MySQL
 - Apache
 - Adminer for database administration

### Setup
```
$ git clone git@github.com:zulfadlisukarno/vagrant-lamp-project.git <your project name>
$ cd <your project name>
$ vagrant up
```
You can directly use <your project name> directory as webroot. For example do phpinfo() and save it in index.php and access it using your browser at http://localhost:8080/

Adminer can be accessed at http://localhost:8080/adminer using this login information:
*Username*: root
*Password*: mysql
Sample database webApp is created and ready for use.
### FAQ
- what if I want to change port from 8080 to something else?
*Edit it in Vagrantfile*