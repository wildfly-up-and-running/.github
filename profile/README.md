# WildFly Up and Running

![wildfly_logo_600px](https://user-images.githubusercontent.com/6193/193811479-522567d4-5b31-4c20-854d-de5703cfe719.png)

WildFly Up and Running is a collection of examples and documentation to help WildFly users have their application up and running on the Cloud.

__[Read the documentation](https://wildfly-up-and-running.github.io/docs/)__.

The examples are individual Git projects that focuses on common use cases.

* [wuar-demo](https://github.com/wildfly-up-and-running/wuar-demo) is a Maven project that builds an application image from a Web deployment which uses Jakarta EE and MicroProfile Config. You can try the application directly using the image [ghcr.io/wildfly-up-and-running/wuar-demo](https://ghcr.io/wildfly-up-and-running/wuar-demo).
* [wuar-tls-demo](https://github.com/wildfly-up-and-running/wuar-tls-demo) shows how to enable TLS on an existing application. It uses the image from [wuar-demo](https://github.com/wildfly-up-and-running/wuar-demo) and provides instructions to generate a certificate, store it in Kubernetes and let WildFly use it for its HTTPS endpoint.
