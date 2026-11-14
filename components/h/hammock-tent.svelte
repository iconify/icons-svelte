<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onmte-l8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hammock-tent" {...props}></Icon>
<style>
:global(.onmte-l8g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5v19m17-19v19M7 10.5q5-1.5 10 0c0 5-2 7.5-5 7.5s-5-2.5-5-7.5Zm-3.5-4l3.5 4m13.5-4l-3.5 4");
}

</style>
