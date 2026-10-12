<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="puicqcbsv"/><path class="o6uo12bkp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:car-top" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o6uo12bkp) {
  d: path("M8.75 8.75c2-1 4.5-1 6.5 0M9 17q3 1.125 6 0M6.75 9.25h-2m12.5 0h2");
}

:global(.puicqcbsv) {
  width: 10.5px;
  height: 18.5px;
  x: 6.75px;
  y: 2.75px;
  rx: 4px;
}

</style>
