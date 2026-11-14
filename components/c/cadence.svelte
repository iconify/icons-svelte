<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pyynccbji"/><path class="qn_to6vho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cadence" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pyynccbji) {
  d: path("M10.106 3h3.788a2.625 2.625 0 0 1 2.563 2.056l2.833 12.75A2.625 2.625 0 0 1 16.728 21H7.272a2.625 2.625 0 0 1-2.562-3.194l2.833-12.75A2.625 2.625 0 0 1 10.106 3M12 17l2-10.75");
}

:global(.qn_to6vho) {
  d: path("M13 9h.5a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H13a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 13 9");
}

</style>
