<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrwdc6bcf"/><path class="wsa8k1bzc"/><path class="kffxb8bqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:git-merge-base" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hrwdc6bcf) {
  d: path("M4 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m12 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.kffxb8bqs) {
  fill: currentColor;
  d: path("M10 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.wsa8k1bzc) {
  d: path("M6 7v1.5c0 3 6 3.5 6 6.5v2m6-10v1.5c0 3-6 3.5-6 6.5");
}

</style>
