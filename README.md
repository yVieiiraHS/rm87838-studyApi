# Ping

API Java com Spring Boot para uso genérico adequada para criação de imagens de implementação CI/CD


Dependencies:
- Spring Web
- [Springdoc OpenAPI](https://springdoc.org/)
```
		<dependency>
			<groupId>org.springdoc</groupId>
			<artifactId>springdoc-openapi-ui</artifactId>
			<version>1.6.14</version>
		</dependency>
```

## Maven

#### Build

```
mvn clean package
```

#### Run

```
mvn spring-boot:run
```

----
## API 


#### Documentação

- http://localhost:8080

#### Endpoints
- http://localhost:8080/ping


## Docker

#### Criando imagem
```
docker build -t ping .
```

#### Listando imagens

```
docker image ls
```

#### Executando a aplicação (Container)

```
docker run -d -p 8080:8080 ping
```

#### Listando Containers em execução

```
docker ps
```

#### Listando Containers encerrados

```
docker ps -a
```

## Github Action

- https://github.com/features/actions

 
 

## Referencias

- https://blog.tericcabrel.com/push-docker-image-docker-hub/
- https://devconnected.com/category/devops/docker/
- https://developer.okta.com/blog/2020/12/28/spring-boot-docker
- https://sterl.org/2021/05/spring-boot-redirect-to-swaggerui/
- https://hub.docker.com/

- https://docs.github.com/en/actions/creating-actions/creating-a-docker-container-action
- https://medium.com/platformer-blog/lets-publish-a-docker-image-to-docker-hub-using-a-github-action-f0b17e5cceb3

- https://docs.github.com/en/actions/learn-github-actions/variables