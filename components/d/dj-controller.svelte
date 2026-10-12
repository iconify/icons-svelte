<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="l0ojli41q"/><circle class="jhn2ch9ax"/><circle class="ifs-v5bqs"/><path class="l517yxbln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dj-controller" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ifs-v5bqs) {
  cx: 17px;
  cy: 12px;
  r: 2px;
}

:global(.jhn2ch9ax) {
  cx: 7px;
  cy: 12px;
  r: 2px;
}

:global(.l0ojli41q) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 2.5px;
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

</style>
