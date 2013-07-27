Tornado Sessions
================

Multi-Backend Session Support for Tornado.  This project attempts to make a pull-request friendly session controller
for the `Tornado Web Server <http://www.tornadoweb.org>`_.

One of the mighty challenges of this project is to provide both syncronous and asyncronous access to backends to allow
for this project to be used by the ioloop as well as wsgi/uwsgi handlers.

For all HTTP based sessions it is good to provide a syncronous requests or urllib2 based session class as well as a
simple and curl compatible tornado.httpclient based class.


Backends Supported
------------------

* MongoDB

  * `PyMongo <http://api.mongodb.org/python/current/>`_
  * `motor <http://motor.readthedocs.org/en/stable/>`_
  
* Redis

  * `redis <https://redis-py.readthedocs.org/en/latest/>`_
  * `tornado-redis <https://github.com/leporo/tornado-redis/>`_
  * webdis
  
* MySQL

  * `MySQLdb <http://mysql-python.sourceforge.net/MySQLdb.html>`_
  
* PostgreSQL

  * `psychopg2 <>`_

* SQLite3
  
* Cookies

  * standard
  * secure

* Encrypted Cookies

  * `tornado-encookie <https://github.com/whardier/tornado-encookie/>`_

Backends Planned
----------------

* MongoDB

  * sleepymongoose
  * nginx
  
* Redis

  * nginx
  
* MySQL

  * nginx
  * adisp/adb
  
* PostgreSQL

  * nginx
  * adisp/adb

