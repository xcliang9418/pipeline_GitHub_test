pipeline {
  agent {
    node {
      label 'mactest'
    }

  }
  stages {
    stage('testmac') {
      agent {
        node {
          label 'mactest'
        }

      }
      steps {
        stash(name: '缓存文件的标记', allowEmpty: false, excludes: null, includes: null, useDefaultExcludes: false)
      }
    }

  }
}