<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xik2-nb7m"/><path class="pxq3s29va"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:frame-mat" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pxq3s29va) {
  d: path("M10 7.5h4A1.5 1.5 0 0 1 15.5 9v6a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 15V9A1.5 1.5 0 0 1 10 7.5");
}

:global(.xik2-nb7m) {
  d: path("M6.625 2.5h10.75A2.625 2.625 0 0 1 20 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875V5.125A2.625 2.625 0 0 1 6.625 2.5");
}

</style>
