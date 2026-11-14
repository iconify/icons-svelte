<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uimv6zbqu"/><path class="vsjdpydik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kick-target-paddle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uimv6zbqu) {
  d: path("M10 3.5za6.5 6.5 0 0 1 6.5 6.5v4a6.5 6.5 0 0 1-6.5 6.5A6.5 6.5 0 0 1 3.5 14v-4A6.5 6.5 0 0 1 10 3.5M16.5 8c4.5 0 4.5 8 0 8");
}

:global(.vsjdpydik) {
  d: path("M6.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m3.5 0h.01");
}

</style>
