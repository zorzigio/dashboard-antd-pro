Hello Volodymyr,

Please see the [Auth0 page](https://auth0.com/docs/quickstart/spa/react/01-login) regarding React login.

The problem I was facing with this template is related to the fact that the routes are exported from the [config.ts](./config/config.ts) file (however I am not and expert in React, so I am sure you can solve this easily)

Please also make sure that once the route cannot be accessed by the user (because for instance the user does not have privileges), the entry does not appear in the sidebar menu.

Thanks