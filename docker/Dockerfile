FROM adoptopenjdk:11.0.11_9-jre-hotspot

RUN mkdir /app
WORKDIR /app

ADD build/*.jar /app/app.jar

ENTRYPOINT java -jar ./app.jar

EXPOSE 8080

