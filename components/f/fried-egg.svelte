<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x-npt07md"/><path class="bnjnom5xi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fried-egg" {...props}></Icon>
<style>
:global(.bnjnom5xi) {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x-npt07md) {
  d: path("M5 14c-2-3 0-8 5-8.5c4-.5 8.5 1.5 10 5S18 19 13 19c-4 0-6.5-1.5-8-5Z");
}

</style>
