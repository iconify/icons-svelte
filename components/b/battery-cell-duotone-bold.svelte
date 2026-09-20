<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cwc9nyz4r"/><path class="k8_5durmd"/><path class="qvytntb8g"/><path class="u-a-7fbnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:battery-cell-duotone-bold" {...props}></Icon>
<style>
:global(.cwc9nyz4r) {
  fill: currentColor;
  d: path("M7 6h10v14H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k8_5durmd) {
  d: path("M7 6h10v14H7Z");
}

:global(.qvytntb8g) {
  d: path("M7 10h10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u-a-7fbnu) {
  d: path("M10 6V3h4v3");
}

</style>
