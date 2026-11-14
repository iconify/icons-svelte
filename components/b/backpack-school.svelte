<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ko6pdmbxq"/><path class="oxg6of9kb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:backpack-school" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ko6pdmbxq) {
  d: path("M12 5.5za7 7 0 0 1 7 7v2a7 7 0 0 1-7 7a7 7 0 0 1-7-7v-2a7 7 0 0 1 7-7m-2.5 0v-1a2.5 2.5 0 0 1 5 0v1");
}

:global(.oxg6of9kb) {
  d: path("M10.5 13.5h3A2.5 2.5 0 0 1 16 16a2.5 2.5 0 0 1-2.5 2.5h-3A2.5 2.5 0 0 1 8 16a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
