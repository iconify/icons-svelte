<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bi741aczb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cd-16-filled" {...props}></Icon>
<style>
:global(.bi741aczb) {
  fill: currentColor;
  d: path("M8 6a2 2 0 1 1 .001 3.999A2 2 0 0 1 8 6m0 3a1 1 0 1 1 0-2a1 1 0 0 1 0 2m0-7a6 6 0 1 0 0 12A6 6 0 0 0 8 2");
}

</style>
