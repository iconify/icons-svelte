<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uwnh69b_r"/><path class="rllvxib4b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bandage-roll" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rllvxib4b) {
  d: path("M10.25 9.75a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 1 1 0-4.5m7 5.25H20a1.25 1.25 0 0 1 1.25 1.25v1.5A1.25 1.25 0 0 1 20 19h-2.75Z");
}

:global(.uwnh69b_r) {
  d: path("M10.25 19a7 7 0 1 1 7-7v7Z");
}

</style>
