<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dmwrntbgf"/><path class="nybxqgb1e"/><circle class="zls1_oujj"/><path class="gwrwmibay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:isolation-room" {...props}></Icon>
<style>
:global(.dmwrntbgf) {
  width: 18.5px;
  height: 18px;
  x: 2.75px;
  y: 3.25px;
  rx: 2.5px;
}

:global(.gwrwmibay) {
  d: path("M7.75 18.25a4.25 4.25 0 0 1 8.5 0Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nybxqgb1e) {
  d: path("M5.75 6.25v12m12.5-12v12");
}

:global(.zls1_oujj) {
  cx: 12px;
  cy: 9px;
  r: 2.5px;
}

</style>
