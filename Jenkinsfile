@Library('test-jenkins-shared-library') _

// codePipeline {
//     image = 'mcr.microsoft.com/dotnet/core/aspnet:3.1'
//     build = 'dotnet build'
//     test = 'dotnet test'
//     gitRepo = {

//     }
// }

pipeline {
    agent any 
    stages {
        stage('checkout') {
            steps {
                gitCheckout(
                    type : 'GitSCM',
                    url : 'https://github.com/yshatheesh1/Natures_css_project.git,
                    branchName : 'master')
                }
            }
        }
    }
// }
// pipeline {
//     agent any {
//         stage('setup') {
//             setupJava([
//                 version: 'java:1.8.0'
//             ]) 
//             setupDotnet([
//                 version: '3.1.0'
//             ])
//             java.setup([
//                 version: '1.9.0',
//                 buildType: 'maven'
//             ])
//             dotnet.setup([
//                 version: '3.1.0'
//             ])
//         }
//         stage('checkout') {
//             checkoutCode([
//                 timeout: 4
//             ])
//         }
//         stage('build') {
//            dotnet.build()
//         }
//         stage('test') {
//             dotnet.test()
//         }
//         stage('sonarScan') {
//             dotnet.sonarScan()
//         }
//     }
// }

// // codePipeline {
// //     docker_image = ppiper/node-browsers
// //     buildType = 'dotnet'
// //     version = '3.1.0'
// //     jobs {
// //         stage('setup') {
// //             buildDotnetEnv()
// //         }
// //         build_all {

// //         }
// //         run_unit_tests {

// //         }
// //         run_cypress_tests {

// //         }
// //         run_sonar_scanner {

// //         }
// //         publish_to_test {
            
// //         }
// //         functional_tests {

// //         }
// //         publish_to_stage {

// //         }
// //         functional_tests_stage {

// //         }
// //         publish_to_prod {

// //         }
// //         functional_tests_prod {

// //         }
// //     }
// // }

