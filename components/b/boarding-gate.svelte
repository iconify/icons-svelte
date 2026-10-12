<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qe1tygbnm"/><path class="ssflydbls"/><path class="o3z3j5btx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boarding-gate" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o3z3j5btx) {
  d: path("M8.75 16.25H15m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

:global(.qe1tygbnm) {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.ssflydbls) {
  d: path("M6.25 5.25h4.5m3 0h4m-12.5 16v-10h13.5v10");
}

</style>
