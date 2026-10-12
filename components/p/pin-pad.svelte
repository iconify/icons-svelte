<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="lrzpc5j9m"/><rect class="mfzpv6biy"/><path class="ig42yes1z"/><path class="ec8d632vc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pin-pad" {...props}></Icon>
<style>
:global(.ec8d632vc) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 14.25h.01m2.99 0h.01m2.99 0h.01M9 17.5h.01m2.99 0h.01m2.99 0h.01");
}

:global(.ig42yes1z) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 10.75h7");
}

:global(.lrzpc5j9m) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 7.25v-3a1 1 0 0 1 1-1h7.5a1 1 0 0 1 1 1v3");
}

:global(.mfzpv6biy) {
  width: 13.5px;
  height: 14px;
  x: 5.25px;
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

</style>
