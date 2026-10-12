<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="gn6dm5-eo"/><path class="topfiybab"/><rect class="gxp6806by"/><path class="eutqeqbom"/><path class="jgyfg-bpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:quest-scroll" {...props}></Icon>
<style>
:global(.eutqeqbom) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.75v3.5");
}

:global(.gn6dm5-eo) {
  width: 16.5px;
  height: 3.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

:global(.gxp6806by) {
  width: 16.5px;
  height: 3.5px;
  x: 3.75px;
  y: 17.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

:global(.jgyfg-bpu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.75h.01");
}

:global(.topfiybab) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 6.25h12.5v11.5H5.75Z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
