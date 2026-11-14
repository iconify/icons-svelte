<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5iingb9p"/><path class="w_hg2rbce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leaf-spinach" {...props}></Icon>
<style>
:global(.e5iingb9p) {
  d: path("M12 18.5q-3.5.25-5.5-2q-2.5-2-2-5Q4 8 6.5 6q2-3.25 5.5-3.5q3.5.25 5.5 3.5q2.5 2 2 5.5q.5 3-2 5q-2 2.25-5.5 2m0 3V6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w_hg2rbce) {
  d: path("M8.5 7.5L12 10l3.5-2.5m-7.5 4l4 2.5l4-2.5");
}

</style>
