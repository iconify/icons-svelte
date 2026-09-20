<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m0ak0bcpt"/><path class="ceyqjyfpz"/><path class="wwrb2gbkc"/><path class="cj8gecc7a"/><path class="mmsmdzb7p"/><path class="dky0phbxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-camera-duotone-thin" {...props}></Icon>
<style>
:global(.ceyqjyfpz) {
  fill: currentColor;
  d: path("M7 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.cj8gecc7a) {
  d: path("M7 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dky0phbxv) {
  d: path("M19 11v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m0ak0bcpt) {
  fill: currentColor;
  d: path("M4 8v6h10V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mmsmdzb7p) {
  d: path("M14 11h5");
}

:global(.wwrb2gbkc) {
  d: path("M4 8v6h10V8Z");
}

</style>
