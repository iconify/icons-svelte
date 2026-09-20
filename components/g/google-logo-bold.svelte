<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wz7ppbi9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:google-logo-bold" {...props}></Icon>
<style>
:global(.wz7ppbi9k) {
  fill: currentColor;
  d: path("M228 128a100 100 0 1 1-22.86-63.64a12 12 0 0 1-18.51 15.28A76 76 0 1 0 203.05 140H128a12 12 0 0 1 0-24h88a12 12 0 0 1 12 12");
}

</style>
