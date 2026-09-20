<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="r19nubd5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:map-pin-simple-line-fill" {...props}></Icon>
<style>
:global(.r19nubd5m) {
  fill: currentColor;
  d: path("M224 216a8 8 0 0 1-8 8H40a8 8 0 0 1 0-16h80v-72.58a56 56 0 1 1 16 0V208h80a8 8 0 0 1 8 8");
}

</style>
