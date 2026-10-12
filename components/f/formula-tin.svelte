<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="zxt2az7as"/><path class="bhaxp4yuf"/><rect class="a_7sod_cd"/><path class="fmpif9znc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:formula-tin" {...props}></Icon>
<style>
:global(.a_7sod_cd) {
  width: 15px;
  height: 13.75px;
  x: 4.5px;
  y: 7.5px;
  rx: 2.5px;
}

:global(.bhaxp4yuf) {
  d: path("M14.5 4H11");
}

:global(.fmpif9znc) {
  d: path("M4.5 11h15M8 14h8v4.25H8Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zxt2az7as) {
  cx: 15.75px;
  cy: 4px;
  r: 1.25px;
}

</style>
