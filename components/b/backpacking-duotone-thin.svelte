<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6aflnb5k"/><path class="gwao277ro"/><path class="a3hsakflq"/><path class="vslz5yb3q"/><path class="x6vx8fhgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backpacking-duotone-thin" {...props}></Icon>
<style>
:global(.a3hsakflq) {
  d: path("M6 16V8a6 6 0 0 1 12 0v8Z");
}

:global(.f6aflnb5k) {
  fill: currentColor;
  d: path("M6 16V8a6 6 0 0 1 12 0v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gwao277ro) {
  fill: currentColor;
  d: path("M3 20.5A1.5 1.5 0 0 1 4.5 19h15a1.5 1.5 0 0 1 1.5 1.5 1.5 1.5 0 0 1 -1.5 1.5h-15A1.5 1.5 0 0 1 3 20.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

:global(.x6vx8fhgp) {
  d: path("M3 20.5A1.5 1.5 0 0 1 4.5 19h15a1.5 1.5 0 0 1 1.5 1.5 1.5 1.5 0 0 1 -1.5 1.5h-15A1.5 1.5 0 0 1 3 20.5");
}

</style>
