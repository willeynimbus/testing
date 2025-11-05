pipeline {
  agent any
  stages {
    stage('clonning the repository'){
      steps{
        echo 'Clonning...'
        checkout scm
      }
    }
    stage('Checking Python'){
      steps{
        sh 'python3 --version'
      }
    }
    stage('Running Python file'){
      steps{
        sh 'python3 python.py'
      }
    }
  }
}
