<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fdzopy_ay"/><path class="wyvjocxcu"/><rect class="j1oksfgqz"/><path class="zpdz8rbaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:perfume" {...props}></Icon>
<style>
:global(.fdzopy_ay) {
  width: 6.5px;
  height: 3px;
  x: 8.75px;
  y: 4.25px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j1oksfgqz) {
  width: 16.5px;
  height: 11.5px;
  x: 3.75px;
  y: 9.75px;
  rx: 3.5px;
}

:global(.wyvjocxcu) {
  d: path("M15.25 5.75h3");
}

:global(.zpdz8rbaf) {
  d: path("M9 15.5h6");
}

</style>
