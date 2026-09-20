<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ali-_7bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:hexagon-48-regular" {...props}></Icon>
<style>
:global(.ali-_7bas) {
  fill: currentColor;
  d: path("M15.427 8.5a.75.75 0 0 0-.655.385l-8.208 14.75a.75.75 0 0 0 0 .73l8.208 14.75a.75.75 0 0 0 .655.385h17.148a.75.75 0 0 0 .656-.385l8.207-14.75a.75.75 0 0 0 0-.73L33.23 8.885a.75.75 0 0 0-.656-.385zm-2.84-.83A3.25 3.25 0 0 1 15.427 6h17.148c1.18 0 2.267.64 2.84 1.67l8.208 14.75a3.25 3.25 0 0 1 0 3.16l-8.208 14.75a3.25 3.25 0 0 1-2.84 1.67H15.427a3.25 3.25 0 0 1-2.84-1.67L4.38 25.58a3.25 3.25 0 0 1 0-3.16z");
}

</style>
