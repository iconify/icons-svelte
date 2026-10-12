<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="a7q8jib6e"/><path class="tz8d1icpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:person-celebrating" {...props}></Icon>
<style>
:global(.a7q8jib6e) {
  cx: 12px;
  cy: 7.25px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tz8d1icpz) {
  d: path("M12 12v4.25m-2.5 5l2.5-5l2.5 5M7 5l1.25 5.5L12 12l3.75-1.5L17 5M4.75 13.5q.24 1.76 2 2q-1.76.24-2 2q-.24-1.76-2-2q1.76-.24 2-2m14.5 0q.24 1.76 2 2q-1.76.24-2 2q-.24-1.76-2-2q1.76-.24 2-2");
}

</style>
