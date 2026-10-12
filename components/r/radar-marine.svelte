<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mmkci1s_q"/><rect class="uo-znoxiv"/><path class="ro1pudbnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:radar-marine" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mmkci1s_q) {
  width: 17.5px;
  height: 2.25px;
  x: 3.25px;
  y: 6px;
  rx: 1.1px;
}

:global(.ro1pudbnu) {
  d: path("M12 12v7.75m-3.5.75h7m1.94-10.86A6 6 0 0 1 15 12.3m4.99-2.29a8.5 8.5 0 0 1-3.11 4.05");
}

:global(.uo-znoxiv) {
  width: 4px;
  height: 3.75px;
  x: 10px;
  y: 8.25px;
  rx: 0.75px;
}

</style>
