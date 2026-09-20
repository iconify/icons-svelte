<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="wc9cnwkrl"/><path class="ff9cpzbqy"/><path class="zk4d2l8to"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:arrow-left" {...props}></Icon>
<style>
:global(.ff9cpzbqy) {
  d: path("M8.974 5.232a1 1 0 0 1 .128 1.408l-3.334 4a1 1 0 1 1-1.536-1.28l3.333-4a1 1 0 0 1 1.409-.128");
}

:global(.n1lsf0bnc) {
  fill: currentColor;
  fill-rule: evenodd;
}

:global(.wc9cnwkrl) {
  d: path("M8.974 14.768a1 1 0 0 1-1.409-.128l-3.333-4a1 1 0 1 1 1.536-1.28l3.334 4a1 1 0 0 1-.128 1.408");
}

:global(.zk4d2l8to) {
  d: path("M6 10a1 1 0 0 1 1-1h8a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1");
}

</style>
