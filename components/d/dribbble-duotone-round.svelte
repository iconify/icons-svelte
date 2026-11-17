<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bhwog2b5s"/><path class="jl6i-4bmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dribbble-duotone-round" {...props}></Icon>
<style>
:global(.bhwog2b5s) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 21a9 9 0 0 1-9-9a9 9 0 0 1 9-9a9 9 0 0 1 9 9a9 9 0 0 1-9 9");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jl6i-4bmp) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 4c5 6 7 10 8 16M4 11c4.5 0 9-1 14-5M7 19c3-3 6-6 13-7M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0");
}

</style>
