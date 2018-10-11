pipeline {
  agent any
  stages {
    stage('Hello World') {
      steps {
        echo 'Hello World :D'
      }
    }
    stage('Start nginx') {
      steps {
        sh 'make start'
      }
    }
  }
}