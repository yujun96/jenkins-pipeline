pipeline {
    agent 
      {docker {
        image 'node:10'
        args '-p 20000:8080'
    } 
      }
    stages {
        stage('Build') { 
            steps {
                // 
                sh 'node -v'
                sh 'echo " hello world" '
            }
        }
    }
}