<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ot_j0v85x"/><path class="lmya8bbwl"/><rect class="z30al_b8u"/><rect class="zxytvhbzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:car-fuse" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lmya8bbwl) {
  d: path("M7.5 9.75h3l3-2.5h3");
}

:global(.ot_j0v85x) {
  width: 17px;
  height: 9px;
  x: 3.5px;
  y: 4px;
  rx: 2.5px;
}

:global(.z30al_b8u) {
  width: 3px;
  height: 6px;
  x: 6px;
  y: 13px;
  rx: 0.75px;
}

:global(.zxytvhbzw) {
  width: 3px;
  height: 6px;
  x: 15px;
  y: 13px;
  rx: 0.75px;
}

</style>
