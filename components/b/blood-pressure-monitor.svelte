<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ox-9axvtc"/><path class="quinmfbzu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blood-pressure-monitor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ox-9axvtc) {
  d: path("M6.875 3.5h4.75A4.375 4.375 0 0 1 16 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-4.75A4.375 4.375 0 0 1 2.5 16.125v-8.25A4.375 4.375 0 0 1 6.875 3.5M6 8h6.5M6 11.75h4.5");
}

:global(.quinmfbzu) {
  d: path("M7.75 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M16 8c5 0 5.5 4.5 3.75 7c-1.5 2-1.25 4.75 1.75 6");
}

</style>
