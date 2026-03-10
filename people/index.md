---
title: People
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}People

Our group brings together Korean researchers and professionals in the nuclear field based in New England. We are passionate about advancing nuclear science and technology, sharing knowledge, and building a supportive community for networking, collaboration, and mentorship.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}
