<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vhv5p_bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-line-down-bold" {...props}></Icon>
<style>
:global(.vhv5p_bsa) {
  fill: currentColor;
  d: path("M47.51 112.49a12 12 0 0 1 17-17L116 147V32a12 12 0 0 1 24 0v115l51.51-51.52a12 12 0 0 1 17 17l-72 72a12 12 0 0 1-17 0ZM216 204H40a12 12 0 0 0 0 24h176a12 12 0 0 0 0-24");
}

</style>
