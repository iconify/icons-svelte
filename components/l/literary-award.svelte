<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouu2q84-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:literary-award" {...props}></Icon>
<style>
:global(.ouu2q84-d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h10v6A5 5 0 0 1 7 9Zm0 2H5a2 2 0 0 0 0 4h2m10-4h2a2 2 0 0 1 0 4h-2m-5 5v3.75M5.5 18Q9 16.75 12 18q3-1.25 6.5 0v3.5q-3.5-1.25-6.5 0q-3-1.25-6.5 0Z");
}

</style>
