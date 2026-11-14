<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="trtgpubah"/><path class="knuashbqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:review-resolve" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.knuashbqo) {
  d: path("M8.5 11.5L11 14l4.5-4.5");
}

:global(.trtgpubah) {
  d: path("M7.75 18.75a8.5 8.5 0 1 0-3-3L3 20.5Z");
}

</style>
