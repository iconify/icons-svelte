<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="fi0i07b4o"/><path class="fk7rtdz_h"/><path class="q2h4d76ol"/><path class="et_xepb2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:oscilloscope" {...props}></Icon>
<style>
:global(.et_xepb2q) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 9.25h.01m-.01 5.5h.01");
}

:global(.fi0i07b4o) {
  width: 18.5px;
  height: 15.5px;
  x: 2.75px;
  y: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.fk7rtdz_h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 7.25H14a1 1 0 0 1 1 1v7.5a1 1 0 0 1-1 1H6.25a1 1 0 0 1-1-1v-7.5a1 1 0 0 1 1-1");
}

:global(.q2h4d76ol) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12q1.05-3.75 2.1 0c1.05 3.75 1.4 2.5 2.1 0s1.4-2.5 2.1 0");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
