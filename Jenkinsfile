pipeline { 
  
   agent any

   stages {
     stage('Update OS') { 
        steps { 
           sh 'sudo yum update' 
        }
     }  
   
     stage('Install Dependencies') { 
        steps { 
           sh 'sudo yum install nodejs npm' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
