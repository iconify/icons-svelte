<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ehzabs01i"/><path class="z907b6bvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:commission-split" {...props}></Icon>
<style>
:global(.ehzabs01i) {
  d: path("M10.5 4a8 8 0 0 0 0 16Zm3 0a8 8 0 0 1 0 16Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z907b6bvk) {
  d: path("M10.5 17a5 5 0 0 1 0-10m3 0a5 5 0 0 1 0 10");
}

</style>
