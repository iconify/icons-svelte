<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zcm1aacul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:flag-pennant-light" {...props}></Icon>
<style>
:global(.zcm1aacul) {
  fill: currentColor;
  d: path("m242 98.33l-184-64A6 6 0 0 0 50 40v176a6 6 0 0 0 12 0v-43.73l180-62.6a6 6 0 0 0 0-11.34M62 159.56V48.44L221.74 104Z");
}

</style>
