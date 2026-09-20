<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="sr3trcc0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:music-note-simple-fill" {...props}></Icon>
<style>
:global(.sr3trcc0h) {
  fill: currentColor;
  d: path("m210.3 56.34l-80-24A8 8 0 0 0 120 40v108.26A48 48 0 1 0 136 184V50.75l69.7 20.91a8 8 0 1 0 4.6-15.32");
}

</style>
