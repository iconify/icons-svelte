<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fbde_z08y"/><path class="eh3r5zbug"/><path class="w3hyiobto"/><path class="jluoio_sz"/><path class="v00cs4edx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:locked-label-duotone-bold" {...props}></Icon>
<style>
:global(.eh3r5zbug) {
  fill: currentColor;
  d: path("M9 13.5h6v3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fbde_z08y) {
  fill: currentColor;
  d: path("M3 6h10l8 8 -8 8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jluoio_sz) {
  d: path("M9 13.5h6v3H9Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v00cs4edx) {
  d: path("M10.5 13.5a1.5 1.5 0 0 1 3 0");
}

:global(.w3hyiobto) {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

</style>
