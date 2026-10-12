<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jx0p6s4hi"/><circle class="ddy7nc0xh"/><rect class="r9ql7wbrx"/><path class="j901znb6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:demolition-ball" {...props}></Icon>
<style>
:global(.ddy7nc0xh) {
  cx: 8.25px;
  cy: 15.25px;
  r: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j901znb6t) {
  d: path("M14.25 13.25h7m-7 4h7");
}

:global(.jx0p6s4hi) {
  d: path("M2.75 6.5L5.5 3.25h2.75v9");
}

:global(.r9ql7wbrx) {
  width: 7px;
  height: 12px;
  x: 14.25px;
  y: 9.25px;
  rx: 1px;
}

</style>
