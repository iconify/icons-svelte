<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g_inlmf6c"/><path class="kg-797_ht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:music-stand" {...props}></Icon>
<style>
:global(.g_inlmf6c) {
  width: 16.5px;
  height: 9.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kg-797_ht) {
  d: path("M7 5.75h10M7 9h10M3 12.25h18m-9 0V19m0 0l-4.5 2.25M12 19l4.5 2.25");
}

</style>
