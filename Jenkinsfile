pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn test'
      }
    }

    stage('Test') {
      steps {
        sh 'mvn test'
      }
    }

    stage('Deliver') {
      steps {
        sh '''echo "Deliver Stage"
echo "gml"'''
      }
    }

  }
}