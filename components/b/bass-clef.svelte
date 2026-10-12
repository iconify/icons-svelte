<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xq6g3_bmq"/><circle class="gcw325b6s"/><circle class="x74ytnb8g"/><circle class="cldbi7bap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bass-clef" {...props}></Icon>
<style>
:global(.cldbi7bap) {
  cx: 19.5px;
  cy: 13px;
  r: 1.25px;
}

:global(.gcw325b6s) {
  cx: 7px;
  cy: 10px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x74ytnb8g) {
  cx: 19.5px;
  cy: 7.5px;
  r: 1.25px;
}

:global(.xq6g3_bmq) {
  d: path("M5.25 9.75c0-3.1 2.4-5.5 5.25-5.5c3.3 0 5.25 2.4 5.25 5.5c0 5.2-4.5 9-10 11");
}

</style>
