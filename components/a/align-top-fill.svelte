<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rv9zgxkkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:align-top-fill" {...props}></Icon>
<style>
:global(.rv9zgxkkp) {
  fill: currentColor;
  d: path("M224 40a8 8 0 0 1-8 8H40a8 8 0 0 1 0-16h176a8 8 0 0 1 8 8m-32 24h-40a16 16 0 0 0-16 16v96a16 16 0 0 0 16 16h40a16 16 0 0 0 16-16V80a16 16 0 0 0-16-16m-88 0H64a16 16 0 0 0-16 16v136a16 16 0 0 0 16 16h40a16 16 0 0 0 16-16V80a16 16 0 0 0-16-16");
}

</style>
