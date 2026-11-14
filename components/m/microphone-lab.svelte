<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="to1asja8w"/><path class="lfy8rmb1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:microphone-lab" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lfy8rmb1d) {
  d: path("M3.75 9.5a5.75 5.75 0 0 0 11.5 0M9.5 15.25V21m-3 0h6m3-3.5V20m3-4.5v6m3-4V20");
}

:global(.to1asja8w) {
  d: path("M9.5 2.5za3 3 0 0 1 3 3v4a3 3 0 0 1-3 3a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3");
}

</style>
