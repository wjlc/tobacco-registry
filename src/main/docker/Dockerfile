FROM openjdk:8-jre-alpine

ENV SPRING_OUTPUT_ANSI_ENABLED=ALWAYS

VOLUME /tmp
EXPOSE 8761
CMD echo "The application will start in 0s..." && \
    java -Djava.security.egd=file:/dev/./urandom -jar /app.war

# add directly the war
ADD *.war /app.war
