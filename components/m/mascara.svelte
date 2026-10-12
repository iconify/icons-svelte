<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bdgi1bc0w"/><path class="litan7nae"/><rect class="exxs1iber"/><path class="vfvbu2x8k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mascara" {...props}></Icon>
<style>
:global(.bdgi1bc0w) {
  width: 4px;
  height: 5.5px;
  x: 10px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.exxs1iber) {
  width: 6px;
  height: 9.5px;
  x: 9px;
  y: 11.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.litan7nae) {
  d: path("M10 5.5h4m-2 3.75v2.25");
}

:global(.vfvbu2x8k) {
  d: path("M9 14.75h6");
}

</style>
