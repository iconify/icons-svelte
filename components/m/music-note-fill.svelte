<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w3rzqkp9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:music-note-fill" {...props}></Icon>
<style>
:global(.w3rzqkp9k) {
  fill: currentColor;
  d: path("m210.3 56.34l-80-24A8 8 0 0 0 120 40v108.26A48 48 0 1 0 136 184V98.75l69.7 20.91A8 8 0 0 0 216 112V64a8 8 0 0 0-5.7-7.66");
}

</style>
