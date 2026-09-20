<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o_tm5hr5z"/><path class="fnfc3vb6o"/><path class="o_8mz3s9v"/><path class="z02hhrbhf"/><path class="mdqmuqzrh"/><path class="rp7ii8bgy"/><path class="fim5wvb3d"/><path class="lhhiiffss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:multiplayer-duotone-bold" {...props}></Icon>
<style>
:global(.fim5wvb3d) {
  d: path("M5.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.fnfc3vb6o) {
  fill: currentColor;
  d: path("M14 8v8h7V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lhhiiffss) {
  d: path("M16.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mdqmuqzrh) {
  d: path("M3 8v8h7V8Z");
}

:global(.o_8mz3s9v) {
  fill: currentColor;
  d: path("M5.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o_tm5hr5z) {
  fill: currentColor;
  d: path("M3 8v8h7V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rp7ii8bgy) {
  d: path("M14 8v8h7V8Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z02hhrbhf) {
  fill: currentColor;
  d: path("M16.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
