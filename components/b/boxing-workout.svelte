<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="smd5nc9bz"/><path class="bitbxoblb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:boxing-workout" {...props}></Icon>
<style>
:global(.bitbxoblb) {
  d: path("M6 12h3.5a2 2 0 0 1 0 4H7m1.25 3h7a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-7A1.25 1.25 0 0 1 7 20.25A1.25 1.25 0 0 1 8.25 19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.smd5nc9bz) {
  d: path("M6 11a6 6 0 0 1 12-1.5V13a6 6 0 0 1-6 6H9a3 3 0 0 1-3-3Z");
}

</style>
