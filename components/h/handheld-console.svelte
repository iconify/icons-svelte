<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="y9ylp9b2p"/><rect class="eumdm_bac"/><path class="plw7pgrcz"/><path class="wxw3awbew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:handheld-console" {...props}></Icon>
<style>
:global(.eumdm_bac) {
  width: 9px;
  height: 6.25px;
  x: 7.5px;
  y: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.plw7pgrcz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 15.75h3m-1.5-1.5v3");
}

:global(.wxw3awbew) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 16.75h.01m2.24-2h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.y9ylp9b2p) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.75h10a2 2 0 0 1 2 2v12.5a4 4 0 0 1-4 4H7a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2");
}

</style>
