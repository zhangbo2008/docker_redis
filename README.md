# docker_redis



2019-10-29,21点38
docker-redis



docker pull redis


docker run --name some-redis1 -p 6380:6379  -d docker.io/redis --requirepass "123456"

docker exec   -ti 340fef977669 redis-cli

auth 123456

set 1 1
get 1
