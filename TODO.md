- flex container component (row will extend this)
- flex item component (column will extend this)
- breadcrumb component
- buttons js plugin (http://getbootstrap.com/docs/4.0/components/buttons/#button-plugin)
- carousel
- automatic ARIA data attrs for link/collapse
  - they go on the link, but we need to lookup the collapse with id=link.href to check its "show" state
    - search through the components and find the one with that id
- class_select trait needs to somehow listen to changes of classes on selected component and re-render
