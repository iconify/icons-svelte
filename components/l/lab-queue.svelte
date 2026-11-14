<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-bfraciy"/><path class="xf9m4yzvw"/><path class="ym1by1zqg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lab-queue" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w-bfraciy) {
  d: path("M3.5 3v8.5c0 1.1.9 2 2 2s2-.9 2-2V3M10 3v8.5c0 1.1.9 2 2 2s2-.9 2-2V3m2.5 0v8.5c0 1.1.9 2 2 2s2-.9 2-2V3");
}

:global(.xf9m4yzvw) {
  fill: currentColor;
  d: path("M3.5 8.5h4v3c0 1.1-.9 2-2 2s-2-.9-2-2Zm6.5 0h4v3c0 1.1-.9 2-2 2s-2-.9-2-2Zm6.5 0h4v3c0 1.1-.9 2-2 2s-2-.9-2-2Z");
}

:global(.ym1by1zqg) {
  d: path("M3 18.5h17.5m-2.75-2.75l2.75 2.75l-2.75 2.75");
}

</style>
