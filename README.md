# pythonapp
App created using docker

## DO this to build the app

```docker
docker-compose build
```

## create a new django app 

```docker
docker-compose run webapp sh -c "django-admin startproject app"
```

## The above code will create a newproject called app 

## now migrate

```docker
docker-compose run webapp sh -c "python manage.py migrate"
```

## now create a new app called project

```docker
docker-compose run webapp sh -c "python manage.py startapp project"
```

## webapp-> webapp is our django service app name

## To stop the container

```docker
docker-compose stop
```
