# jersey-practice
Jersey web server

# simple-service

```bash
# https://jersey.github.io/documentation/latest/user-guide.html#new-from-archetype
mvn archetype:generate \
  -DarchetypeArtifactId=jersey-quickstart-grizzly2 \
  -DarchetypeGroupId=org.glassfish.jersey.archetypes \
  -DinteractiveMode=false \
  -DgroupId=com.example \
  -DartifactId=simple-service \
  -Dpackage=com.example \
  -DarchetypeVersion=2.27

cd simple-service
mvn clean test

mvn exec:java
```

Access http://localhost:8080/myapp/myresource
