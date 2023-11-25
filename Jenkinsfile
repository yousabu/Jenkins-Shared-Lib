@Library("test-lib") _
pipeline {
  agent any
  stages {
    stage('testlib') {
        steps {
            helloWorldExternal(name:"Youssef", dayOfWeek:"Saturday")
        }
    }
  }
}
