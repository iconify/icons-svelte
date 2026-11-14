<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_tnpmbnh"/><path class="wvh2n2bll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cabinet-meeting" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o_tnpmbnh) {
  d: path("M9 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0M6.5 19c0-3.5 2.25-5.25 5.5-5.25s5.5 1.75 5.5 5.25m-15-8a2 2 0 1 0 4 0a2 2 0 1 0-4 0m15 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.wvh2n2bll) {
  d: path("M2.5 19h19m-19 0c0-2 1-3.25 2-3.25s1.75.5 2.25 1.25m14.75 2c0-2-1-3.25-2-3.25s-1.75.5-2.25 1.25");
}

</style>
