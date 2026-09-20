<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ta9q4p8ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:align-top-simple-fill" {...props}></Icon>
<style>
:global(.ta9q4p8ik) {
  fill: currentColor;
  d: path("M208 32a8 8 0 0 1-8 8H56a8 8 0 0 1 0-16h144a8 8 0 0 1 8 8m-48 24H96a16 16 0 0 0-16 16v152a16 16 0 0 0 16 16h64a16 16 0 0 0 16-16V72a16 16 0 0 0-16-16");
}

</style>
