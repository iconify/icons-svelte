<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kta4y0u5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-half-fill-24-filled" {...props}></Icon>
<style>
:global(.kta4y0u5q) {
  fill: currentColor;
  d: path("M4 12a8 8 0 1 1 16 0zm8-10C6.477 2 2 6.477 2 12s4.477 10 10 10s10-4.477 10-10S17.523 2 12 2");
}

</style>
