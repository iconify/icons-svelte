<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="xoarjdbio"/><path class="aetj8_bfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crescent-shape" {...props}></Icon>
<style>
:global(.aetj8_bfg) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.83 16.57h.01");
}

:global(.xoarjdbio) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.02 3.98a8.51 8.51 0 1 0 12.49 7.8a7.36 7.36 0 0 1-12.49-7.8");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
