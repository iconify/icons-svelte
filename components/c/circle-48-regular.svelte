<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zj3l4ybtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-48-regular" {...props}></Icon>
<style>
:global(.zj3l4ybtx) {
  fill: currentColor;
  d: path("M24 6.5C14.335 6.5 6.5 14.335 6.5 24S14.335 41.5 24 41.5S41.5 33.665 41.5 24S33.665 6.5 24 6.5M4 24C4 12.954 12.954 4 24 4s20 8.954 20 20s-8.954 20-20 20S4 35.046 4 24");
}

</style>
