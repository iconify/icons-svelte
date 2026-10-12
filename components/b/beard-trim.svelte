<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="plqfcy4ey"/><path class="hwczi_gsc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:beard-trim" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwczi_gsc) {
  d: path("M8 14.25c1.5 0 2.75-.5 4-1.5c1.25 1 2.5 1.5 4 1.5c-1 1.5-2.5 2-4 1.25c-1.5.75-3 .25-4-1.25m2.25 4h3.5");
}

:global(.plqfcy4ey) {
  d: path("M4.25 7v4.5c0 5.5 3.5 9.75 7.75 9.75s7.75-4.25 7.75-9.75V7q-1.5 4.5-4.5 4.5h-6.5q-3 0-4.5-4.5");
}

</style>
