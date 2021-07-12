# cannot-parse-result-path-string-Android-studio-Error-
//solution for Error : cannot parse result path string  in android studio after adding firebase realtime database


//Edit in build.gradle module(app) file :

plugins {
    id 'com.android.application'
    id 'com.google.gms.google-services'

}


dependencies {
  testImplementation 'junit:junit:4.13.2'
  
  implementation  'com.google.firebase:firebase-bom:28.2.1'

}


//Edit in build.gradle (project) file :

dependecies{
        classpath "com.android.tools.build:gradle:4.1.3"
}
