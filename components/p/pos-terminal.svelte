<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="wgot8sb2v"/><path class="aneic79nl"/><path class="z4t0o-brg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pos-terminal" {...props}></Icon>
<style>
:global(.aneic79nl) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 10V4.25a1.5 1.5 0 0 1 1.5-1.5h5.5a1.5 1.5 0 0 1 1.5 1.5V10Z");
}

:global(.wgot8sb2v) {
  width: 14.5px;
  height: 14px;
  x: 4.75px;
  y: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z4t0o-brg) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 14.5h.01m3.24 0h.01m3.24 0h.01m-6.51 3.25h.01m3.24 0h.01m3.24 0h.01");
}

</style>
