<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vzahjtbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:google-logo-thin" {...props}></Icon>
<style>
:global(.vzahjtbbx) {
  fill: currentColor;
  d: path("M220 128a92 92 0 1 1-21-58.55a4 4 0 0 1-6.17 5.1A84 84 0 1 0 211.91 132H128a4 4 0 0 1 0-8h88a4 4 0 0 1 4 4");
}

</style>
