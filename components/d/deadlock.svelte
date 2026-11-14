<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iu0rxjxlb"/><path class="cllxm0byq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:deadlock" {...props}></Icon>
<style>
:global(.cllxm0byq) {
  d: path("M10 10.5V7a4 4 0 0 1 8 0v3.5m-6 4v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iu0rxjxlb) {
  d: path("M7.875 10.5h8.25a4.375 4.375 0 0 1 4.375 4.375v2.25a4.375 4.375 0 0 1-4.375 4.375h-8.25A4.375 4.375 0 0 1 3.5 17.125v-2.25A4.375 4.375 0 0 1 7.875 10.5M6 10.5V7a4 4 0 0 1 8 0v3.5");
}

</style>
