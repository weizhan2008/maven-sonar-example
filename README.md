This example demonstrates how to analyze a simple Java Maven project.

![](https://travis-ci.org/mebusw/maven-sonar-example.svg)

Prerequisites
=============
* [SonarQube](http://www.sonarsource.org/downloads/) 2.12 or higher
* Maven 2.2.1 or higher

Usage
=====
* Build the project:

        mvn clean install

* Run tests:

        mvn test

* Analyze it with SonarQube using Maven:

        mvn sonar:sonar
