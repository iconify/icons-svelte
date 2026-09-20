<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="diuk7r84y"/><path class="ugr3wobuy"/><path class="h8uaxgswm"/><path class="c7dgfu7wx"/><path class="qynh2c4wy"/><path class="cwwg2gv6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:object-store-duotone-regular" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.cwwg2gv6o) {
  d: path("M13 13a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

:global(.diuk7r84y) {
  fill: currentColor;
  d: path("M7 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h8uaxgswm) {
  d: path("M4 8v12h16V8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qynh2c4wy) {
  d: path("M7 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ugr3wobuy) {
  fill: currentColor;
  d: path("M13 13a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
