<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="lo_lt5b5d"/><path class="dlw4n-rre"/><path class="ikb95b_4o"/><path class="cq44-0b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:graphics-tablet" {...props}></Icon>
<style>
:global(.cq44-0b-z) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11 15.75l6.25-6.25");
}

:global(.dlw4n-rre) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 4.75v14.5");
}

:global(.ikb95b_4o) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 9.5h.01m-.01 5h.01");
}

:global(.lo_lt5b5d) {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
