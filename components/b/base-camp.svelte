<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n50xzfbrc"/><path class="spg5s-bma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:base-camp" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n50xzfbrc) {
  d: path("m3 20.5l5-11l5 11");
}

:global(.spg5s-bma) {
  d: path("M11.25 16.75L15.5 4.5l5.5 16m-18.5 0h19M6 20.5l2-4l2 4");
}

</style>
