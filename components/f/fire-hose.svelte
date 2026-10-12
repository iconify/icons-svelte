<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><circle class="b405utblj"/><circle class="fkwkb8hzx"/><path class="pld_2hbet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fire-hose" {...props}></Icon>
<style>
:global(.a_-q_pb0z) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

:global(.b405utblj) {
  cx: 10.5px;
  cy: 11px;
  r: 4.5px;
}

:global(.fkwkb8hzx) {
  cx: 10.5px;
  cy: 11px;
  r: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pld_2hbet) {
  d: path("M10.5 15.5h6.25L18 17");
}

</style>
