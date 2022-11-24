## Personal-Zsh-Shell ##
My personal setup zsh shell

[Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)

```
export LANG=en_US.UTF-8
export PATH="$PATH:/Users/yoesuv/Programs/flutter/bin"

#Android
export ANDROID_HOME=/Users/yoesuv/Programs/Android/sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/platform-tools

alias gfo="git fetch origin"
alias gfop="git fetch origin --prune"
alias gpull="git pull"
alias gita="git add ."
alias gits="git status"
alias gitpo="git push -u origin"
alias gitpdev="git push -u origin develop"
alias gitcm="git commit -am"
alias gitc="git checkout"

alias gw="./gradlew"
alias gwc="./gradlew clean"
alias gwbdev="./gradlew bundleDevelopmentRelease"
alias gwadev="./gradlew assembleDevelopmentRelease"
alias gwbstg="./gradlew bundleStagingRelease"
alias gwastg="./gradlew assembleStagingRelease"
alias gwbhotf="./gradlew bundleHotfixRelease"
alias gwahotf="./gradlew assembleHotfixRelease"
alias gwbprod="./gradlew bundleProductionRelease"
alias gwaprod="./gradlew assembleProductionRelease"
alias gwl="./gradlew lint"

alias fl="flutter"
alias flv="flutter --version"
alias flup="flutter upgrade"
alias flr="flutter run"
alias flrv="flutter run -v"
alias flc="flutter clean"
alias flpg="flutter pub get"
alias flemu="flutter emulators"
alias flemu28="flutter emulators --launch Pixel_3_API_28"
alias flemu29="flutter emulators --launch Pixel_3a_API_29"
alias flemu30="flutter emulators --launch Pixel_4_API_30"
alias flemu31="flutter emulators --launch Pixel_5_API_31"
alias flemuios="open -a Simulator"
alias flrdev="flutter run --flavor development"
alias flrstg="flutter run --flavor staging"
alias flrprod="flutter run --flavor production"
alias flbdev="flutter build apk --flavor development"
alias flbstg="flutter build apk --flavor staging"
alias flbprod="flutter build apk --flavor production"

alias exsa="npx expo start --android"
alias exsi="npx expo start --ios"
alias rnstart="clear && npx react-native start"
alias rnandroid="clear && npx react-native run-android"
alias rnandroiddev="clear && npx react-native run-android --variant=developmentDebug"
alias rnandroidstaging="clear && npx react-native run-android --variant=stagingDebug"
alias rnandroidprod="clear && npx react-native run-android --variant=productionDebug"

alias clr="clear"
alias rmss="rm ~/Desktop/*.png"
alias adbresetperm="adb shell pm reset-permissions"
```
