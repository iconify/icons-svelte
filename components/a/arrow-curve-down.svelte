<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="an8in5bao"/><path class="paivv5b1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-curve-down" {...props}></Icon>
<style>
:global(.an8in5bao) {
  d: path("M3.75 4.75c8 0 13.25 4.75 13.25 14.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.paivv5b1d) {
  d: path("m13 15.25l4 4l4-4");
}

</style>
