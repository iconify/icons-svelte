<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kgcahyb8p"/><path class="ztvpyw4uw"/><circle class="u9zd92bgx"/><circle class="t21ih2v7z"/><path class="lq0twvbsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boombox" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kgcahyb8p) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 8px;
  rx: 2px;
}

:global(.lq0twvbsf) {
  d: path("M10.75 11.5h2.5");
}

:global(.t21ih2v7z) {
  cx: 16px;
  cy: 14.75px;
  r: 2.5px;
}

:global(.u9zd92bgx) {
  cx: 8px;
  cy: 14.75px;
  r: 2.5px;
}

:global(.ztvpyw4uw) {
  d: path("M6.5 8V5.5A1.5 1.5 0 0 1 8 4h8a1.5 1.5 0 0 1 1.5 1.5V8");
}

</style>
