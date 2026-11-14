<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vg434_voi"/><path class="os1kogbim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:diaper-cloth" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.os1kogbim) {
  d: path("M6.75 7.75h2A1.25 1.25 0 0 1 10 9a1.25 1.25 0 0 1-1.25 1.25h-2A1.25 1.25 0 0 1 5.5 9a1.25 1.25 0 0 1 1.25-1.25m8.5 0h2A1.25 1.25 0 0 1 18.5 9a1.25 1.25 0 0 1-1.25 1.25h-2A1.25 1.25 0 0 1 14 9a1.25 1.25 0 0 1 1.25-1.25");
}

:global(.vg434_voi) {
  d: path("M2.5 5h19v6.5c-3 .5-5.5 3-6 7.5h-7c-.5-4.5-3-7-6-7.5Z");
}

</style>
