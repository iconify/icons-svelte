<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x0fr2ubtt"/><rect class="b4gkz47jx"/><rect class="fu4a-912q"/><rect class="x8xky0_1v"/><rect class="lx_-1-vno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bounding-box" {...props}></Icon>
<style>
:global(.b4gkz47jx) {
  width: 3.5px;
  height: 3.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 0.75px;
}

:global(.fu4a-912q) {
  width: 3.5px;
  height: 3.5px;
  x: 17.75px;
  y: 2.75px;
  rx: 0.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lx_-1-vno) {
  width: 3.5px;
  height: 3.5px;
  x: 2.75px;
  y: 17.75px;
  rx: 0.75px;
}

:global(.x0fr2ubtt) {
  d: path("M6.25 4.5h11.5m1.75 1.75v11.5m-1.75 1.75H6.25M4.5 17.75V6.25");
}

:global(.x8xky0_1v) {
  width: 3.5px;
  height: 3.5px;
  x: 17.75px;
  y: 17.75px;
  rx: 0.75px;
}

</style>
