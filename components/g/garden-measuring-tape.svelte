<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iymmkma3v"/><path class="kqgd4xbjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:garden-measuring-tape" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iymmkma3v) {
  d: path("M5.5 4.5H14a3 3 0 0 1 3 3V19H5.5a3 3 0 0 1-3-3V7.5a3 3 0 0 1 3-3");
}

:global(.kqgd4xbjd) {
  d: path("M6.75 11.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0M17 15.5h4.5V19H17");
}

</style>
