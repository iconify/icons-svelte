<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="anc3mqbkz"/><path class="iopr4tvqy"/><path class="w8nt-wy2u"/><circle class="xn3dtybmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:keylogger" {...props}></Icon>
<style>
:global(.anc3mqbkz) {
  width: 13.5px;
  height: 10.5px;
  x: 2.75px;
  y: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.iopr4tvqy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 12.25h.01m3.49 0h.01m3.49 0h.01");
}

:global(.w8nt-wy2u) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 16h7");
}

:global(.xn3dtybmu) {
  cx: 18.75px;
  cy: 5.25px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
