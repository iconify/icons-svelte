<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dxagzus4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:map-pin-simple-bold" {...props}></Icon>
<style>
:global(.dxagzus4y) {
  fill: currentColor;
  d: path("M188 72a60 60 0 1 0-72 58.79V232a12 12 0 0 0 24 0V130.79A60.09 60.09 0 0 0 188 72m-60 36a36 36 0 1 1 36-36a36 36 0 0 1-36 36");
}

</style>
