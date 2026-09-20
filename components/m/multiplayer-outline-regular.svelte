<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mdqmuqzrh"/><path class="rp7ii8bgy"/><path class="fim5wvb3d"/><path class="lhhiiffss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:multiplayer-outline-regular" {...props}></Icon>
<style>
:global(.fim5wvb3d) {
  d: path("M5.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.lhhiiffss) {
  d: path("M16.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mdqmuqzrh) {
  d: path("M3 8v8h7V8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rp7ii8bgy) {
  d: path("M14 8v8h7V8Z");
}

</style>
