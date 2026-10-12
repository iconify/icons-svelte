<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ji-lwpszm"/><path class="q63y-pbsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:finger-paint" {...props}></Icon>
<style>
:global(.ji-lwpszm) {
  width: 11px;
  height: 9.75px;
  x: 6.25px;
  y: 11.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 4.5px;
}

:global(.q63y-pbsz) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 9.25V7.5m3 1.25v-4m3 4V4m3 5.25V6m3.25 9.25l.75-2.75");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
