# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

## Setup

```
$ docker-compose build
$ docker-compose up
```

clear

```
$ docker-compose build --no-cache
```

db-create

```
$ docker-compose run app rails db:create
```

webpacker

```
$ docker-compose run app rails webpacker:install
```

rspec version check

```
$ docker-compose run app rspec -v
```

rspec

```
$ docker-compose exec app bash

root@.....:/myapp# rails spec
```
