# A simple pgadmin docker configuration

## Docker

#### Prerequisites

Download && install **docker**
- [For Mac](https://download.docker.com/mac/stable/Docker.dmg)
- [For Windows](https://download.docker.com/win/stable/InstallDocker.msi)
- [For Linux](https://docs.docker.com/engine/getstarted/step_one/#docker-for-linux)

Download && install **docker-compose**
- [Instructions](https://docs.docker.com/compose/install/)

Download && install **docker-machine**
- [Instructions](https://docs.docker.com/machine/install-machine/)


#### Configure environment

- Update default **user**, **pass** and **db** for postgress: `docker/local/pgadmin/.env`.
- Update default **user** and **pass** for **pgadmin**: `docker/local/pgadmin/.env`.


#### Run services using `docker-compose`

Just run:
```
cd docker/local
docker-compose up
```