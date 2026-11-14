<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dlp22yjpb"/><path class="lomys926c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:goal-setting" {...props}></Icon>
<style>
:global(.dlp22yjpb) {
  d: path("M3 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lomys926c) {
  d: path("M7.5 13a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m3.5 0l9-9m-2.5-1l3.25.25L21 6.5");
}

</style>
