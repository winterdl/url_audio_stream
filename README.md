# url_audio_stream

Dart plugin to live stream audio URLs. The package will accept both HTTP and HTTPs urls for streaming. Specific bitrates for the streams will depend on the native application design, which is listed below. 

## Android
Android's provided media player is used to stream the audio. This allows for starting, stopping, and pausing the live stream. 

### HTTP Streams
Android requires an edit to your android manifest to allow connection to non-HTTP sources, follow this [link](https://stackoverflow.com/questions/51902629/how-to-allow-all-network-connection-types-http-and-https-in-android-9-pie) to edit the manifest
