# Mobile Chrome Packaged App API Implementation Status

See the [reference guide for building Chrome Packaged Apps](http://developer.chrome.com/apps/about_apps.html) on Desktop.

This list tracks API support on mobile.

_Current as of Sept 2013_.

* [alarms](https://github.com/MobileChromeApps/chrome-cordova/tree/master/plugins/chrome.alarms)
    * Working on Android and iOS.
    * Caveat: on iOS alarms only fire when app is active (foreground).
* [fileSystem](https://github.com/MobileChromeApps/chrome-cordova/tree/master/plugins/chrome.fileSystem)
    * Working on Android and iOS.
* [i18n](https://github.com/MobileChromeApps/chrome-cordova/tree/master/plugins/chrome.i18n)
    * JS methods work (`chrome.i18n.getMessage()` and `chrome.i18n.getAcceptLanguages()`)
    * CSS placeholders not implemented
* [identity](https://github.com/MobileChromeApps/chrome-cordova/tree/master/plugins/chrome.identity)
    * Working on Android and iOS
* [idle](https://github.com/MobileChromeApps/chrome-cordova/tree/master/plugins/chrome.idle)
    * Working on Android and iOS.
* [notifications](https://github.com/MobileChromeApps/chrome-cordova/tree/master/plugins/chrome.notifications)
    * Working on Android only
* [power](https://github.com/MobileChromeApps/chrome-cordova/tree/master/plugins/chrome.power)
    * Working on Android and iOS.
* [socket](https://github.com/MobileChromeApps/chrome-cordova/tree/master/plugins/chrome.socket)
    * Working on Android and iOS
* [storage](https://github.com/MobileChromeApps/chrome-cordova/tree/master/plugins/chrome.storage)
    * local storage Working on Android and iOS
    * sync storage does not sync, but works like storage.local
* [syncFileSystem](https://github.com/MobileChromeApps/chrome-cordova/tree/master/plugins/chrome.syncFileSystem)
    * Alpha quality on iOS and Android.

## Not yet supported APIs

* bluetooth
* commands
* contextMenus
* mediaGalleries
* notifications
* permissions
* pushMessaging
* serial
* tts
* types
* usb
* webstore
* experimental.record
* experimental.systemInfo.cpu
* experimental.systemInfo.display
* experimental.systemInfo.memory
* experimental.systemInfo.storage
* webview
