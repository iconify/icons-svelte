<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="r-ub_ybqe"/><path class="h0757nbba"/><path class="vge_ec3ru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:app-window-plus" {...props}></Icon>
<style>
:global(.h0757nbba) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 6.5h.01m3.49 0h.01m3.49 0h.01");
}

:global(.r-ub_ybqe) {
  width: 18.5px;
  height: 17.5px;
  x: 2.75px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.vge_ec3ru) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.75h17");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
