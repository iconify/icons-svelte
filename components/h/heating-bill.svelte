<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t_r375bwi"/><path class="p4uynftwf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:heating-bill" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p4uynftwf) {
  d: path("M12.5 7.5q0-1-2.5-1t-2.5 2t2.5 2t2.5 2t-2.5 2t-2.5-1M18 14c1 1.5 3 2.5 3 4.75a3 3 0 0 1-6 0c0-1 .5-1.75 1.25-2.25c0 .75.5 1.25 1 1.25c0-1.25 0-2.75.75-3.75");
}

:global(.t_r375bwi) {
  d: path("M12.173 18.884L12 19l-2-1.5L7.75 19l-2-1.5L3.5 19V2.5h13v9.1M10 5.25v9.5");
}

</style>
