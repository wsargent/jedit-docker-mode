# Docker mode for jEdit

Nothing fancy, just syntax highlighting.

## Installation

Open up your modes folder by going to the Menu "Utilities / Settings Directory" and then clicking on "modes"

Store docker.xml in there.

Add this into the `catalog` file:

```xml
<MODE NAME="docker"
      FILE="docker.xml"
      FILE_NAME_GLOB="Dockerfile"
/>
```
