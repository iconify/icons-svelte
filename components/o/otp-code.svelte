<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="rogdlcbqf"/><path class="p2pcalb3f"/><path class="pvh7ewp6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:otp-code" {...props}></Icon>
<style>
:global(.p2pcalb3f) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 12h.01m3.49 0h.01m3.49 0h.01m3.49 0h.01");
}

:global(.pvh7ewp6v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 18.25h3");
}

:global(.rogdlcbqf) {
  width: 15px;
  height: 18.5px;
  x: 4.5px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.75px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
