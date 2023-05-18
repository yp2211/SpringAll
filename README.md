# SpringAll

spring:
#  datasource:
#    driver-class-name: com.mysql.cj.jdbc.Driver
#    url: jdbc:mysql://127.0.0.1:3306/springbatch
#    username: root
#    password: 123456
  batch:
    job:
      enabled: true
#    initialize-schema: embedded
  datasource:
    url: jdbc:h2:mem:dbtest
#    url: jdbc:h2:file:/data/sample
#    url: jdbc:h2:file:C:/data/sample (Windows only)
#    data: classpath:db/schema-h2.sql
#    schema: classpath:db/schema-drop-h2.sql
    username: sa
    password:
    driver-class-name: org.h2.Driver
  #    initialize: true
  h2:
    console:
      enabled: true
#      path: /h2
#      settings:
#        web-allow-others: true
#  jpa:
#    hibernate:
#      ddl-auto: update
#    show-sql: true
#    properties:
#      hibernate:
#        dialect: org.hibernate.dialect.H2Dialect
#    database-platform: org.hibernate.dialect.H2Dialect
