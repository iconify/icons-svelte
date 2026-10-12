<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="no7ya_sep"/><rect class="nst5q0sxj"/><circle class="w4wqpfbkp"/><path class="xqntkvdws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:camera-compact" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.no7ya_sep) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 2.5px;
}

:global(.nst5q0sxj) {
  width: 4px;
  height: 3px;
  x: 5px;
  y: 4.25px;
  rx: 1px;
}

:global(.w4wqpfbkp) {
  cx: 14.75px;
  cy: 13.5px;
  r: 3.5px;
}

:global(.xqntkvdws) {
  d: path("M5.75 10.5h2.5");
}

</style>
