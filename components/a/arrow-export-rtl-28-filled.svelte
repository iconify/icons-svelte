<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="xqcbmzbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-export-rtl-28-filled" {...props}></Icon>
<style>
:global(.xqcbmzbnw) {
  fill: currentColor;
  d: path("M25 5a1 1 0 0 1 1 1v16a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1M8.793 6.793a1 1 0 0 1 1.414 1.414L5.414 13H21a1 1 0 0 1 0 2H5.414l4.793 4.793a1 1 0 0 1-1.414 1.414l-6.5-6.5a1 1 0 0 1 0-1.414z");
}

</style>
