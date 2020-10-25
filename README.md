## Fibonacci-EB
### The fibonacci calculator with node.js running on docker and AWS elastic beanstalk. Starting Oct. 2020 it is possible to use a docker-compose.yml file to deploy a multi-container app onto EB AL2 environment, which is utilized in this project.

Images used:
- postgres
- redis
- worker (built to handle calculations)
- api (built to handle queries)
- client (bulit, frontend)
- nginx

_Note: check the managed version of the same app, which uses AWS managed services, as well as older version of docker platform on AWS EB._
