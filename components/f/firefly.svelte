<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="e9-7-8-2z"/><path class="earikv5qp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:firefly" {...props}></Icon>
<style>
:global(.e9-7-8-2z) {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

:global(.earikv5qp) {
  d: path("M10.25 9c-2.75-2-5.5-2.25-7.5-.5c1 2.75 4 3.5 7.5.5m3.5 0c2.75-2 5.5-2.25 7.5-.5c-1 2.75-4 3.5-7.5.5M12 11.5c1.75 0 3 2 3 4.5s-1.25 4.5-3 4.5s-3-2-3-4.5s1.25-4.5 3-4.5m-5.25 5.75l-2 1.25m12.5-1.25l2 1.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
