pipeline {
    agent any
    stages{
        stage 'checkout'{
            steps{

            }
        }
        stage ('build') {
            steps{
              sh 'echo iam builder'
            }
            
            }
         stage ('test') {
            steps{
                sh 'echo iam tester'
               }
            }
         stage ('deploy') {
            steps{

                sh 'echo iam deployer'
                
            }
        }
        
    }
}
