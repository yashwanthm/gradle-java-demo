

Install OpenJDK using
https://developers.redhat.com/products/openjdk/overview - 

https://adoptium.net/


# specify your jar file config.
On build.gradle
```
jar {
  manifest {
    attributes(
        'Main-Class': 'demo.App'
    )
  }
} ```

Esure that you are selecting a runtime version that's same as your machine

