FROM livingobjects/jre8:latest

ENV SPRING_OUTPUT_ANSI_ENABLED=ALWAYS \
    JAVA_OPTS=""
    
ADD *.jar app.jar

CMD echo "The application will start " && \
    java ${JAVA_OPTS} -Djava.security.egd=file:/dev/./urandom -jar /app.jar

EXPOSE 8082