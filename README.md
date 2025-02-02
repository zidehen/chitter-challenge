Chitter Challenge

Challenge:
-------

We are going to write a small Twitter clone that will allow the users to post messages to a public stream.

Features:
-------

```
STRAIGHT UP

As a Maker
So that I can let people know what I am doing  
I want to post a message (peep) to chitter

As a maker
So that I can see what others are saying  
I want to see all peeps in reverse chronological order

As a Maker
So that I can better appreciate the context of a peep
I want to see the time at which it was made

As a Maker
So that I can post messages on Chitter as me
I want to sign up for Chitter

HARDER

As a Maker
So that only I can post messages on Chitter as me
I want to log in to Chitter

As a Maker
So that I can avoid others posting messages on Chitter as me
I want to log out of Chitter

ADVANCED

As a Maker
So that I can stay constantly tapped in to the shouty box of Chitter
I want to receive an email if I am tagged in a Peep
```

Technical Approach:
-----

In this unit, you integrated a database into Bookmark Manager using the `PG` gem and `SQL` queries. You can continue to use this approach when building Chitter Challenge.

Notes on functionality:
------

* You don't have to be logged in to see the peeps.
* Makers sign up to chitter with their email, password, name and a username (e.g. samm@makersacademy.com, password123, Sam Morgan, sjmog).
* The username and email are unique.
* Peeps (posts to chitter) have the name of the maker and their user handle.
* Your README should indicate the technologies used, and give instructions on how to install and run the tests.

Comments:
------
I was only able to complete first two user stories. 

### To set up the chitter database:
1. Connect to 'psql'
2. Create the database using the psql command 'CREATE DATABASE chitter;'
3. Connect to the database using the pqsl command '\c chitter;'
4. Run the SQL query saved in the 'db/migrations' folder in the file '01_create_peeps_table.sql'

### To set up the chitter_test database:
1. Connect to 'psql'
2. Create the database using the psql command 'CREATE DATABASE chitter_test;'
3. Connect to the database using the pqsl command '\c chitter_test;'
4. Run the SQL query saved in the 'db/migrations' folder in the file '01_create_peeps_table.sql'