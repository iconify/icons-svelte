<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g28i6yb7h"/><path class="mftdaepvv"/><path class="ns_-3dj2i"/><path class="oz4rn3bss"/><path class="u-a-7fbnu"/><path class="n0k4ov7kr"/><path class="ai7mlsqqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:carry-on-duotone-thin" {...props}></Icon>
<style>
:global(.ai7mlsqqn) {
  d: path("M15 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.g28i6yb7h) {
  fill: currentColor;
  d: path("M5 8a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
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

:global(.mftdaepvv) {
  fill: currentColor;
  d: path("M7 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0k4ov7kr) {
  d: path("M7 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ns_-3dj2i) {
  fill: currentColor;
  d: path("M15 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.oz4rn3bss) {
  d: path("M5 8a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.u-a-7fbnu) {
  d: path("M10 6V3h4v3");
}

</style>
