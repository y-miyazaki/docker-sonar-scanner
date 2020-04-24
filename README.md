# Action sonar-scanner for SonarQube

## Overview

This repository maintains a Dockerfile that runs the sonar-scanner command.  
https://hub.docker.com/r/ymiyazakixyz/sonar-scanner/tags

## Description
SonarQube empowers all developers to write cleaner and safer code.
Join an Open Community of more than 120k users.  
`You need to provide a server for SonarQube. This Dockerfile only sends the result of sonar-scanner to Sonarqube server. `  
The sonar-project.properties has been uploaded as an example, so please refer to it.

### Action sonar-scanner
```
$ docker pull ymiyazakixyz/sonar-scanner:latest
$ docker run -i --rm -v $PWD:/workspace --name sonar-scanner ymiyazakixyz/sonar-scanner:latest -Dsonar.projectName={your project name} -Dsonar.projectKey={your project key} -Dsonar.projectVersion={project version}
```

## Required

- Docker  
  https://www.docker.com/
- SonarQube  
  https://www.sonarqube.org/

## Other Link

- Docker  
  https://www.docker.com/
- SonarQube  
  https://www.sonarqube.org/
- SonarQube Analysis Parameters  
  https://docs.sonarqube.org/latest/analysis/analysis-parameters/

## Note
