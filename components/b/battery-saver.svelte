<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f15wrccqb"/><path class="xu-ux3b6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:battery-saver" {...props}></Icon>
<style>
:global(.f15wrccqb) {
  d: path("M6.875 7h7.75A4.375 4.375 0 0 1 19 11.375v1.25A4.375 4.375 0 0 1 14.625 17h-7.75A4.375 4.375 0 0 1 2.5 12.625v-1.25A4.375 4.375 0 0 1 6.875 7M21.5 10.5v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xu-ux3b6d) {
  d: path("M7 14.5c0-3 2.25-5 7-5c0 3-2 5-7 5");
}

</style>
