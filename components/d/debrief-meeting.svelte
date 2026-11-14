<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y3l9vuvbt"/><path class="vtpgnebtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:debrief-meeting" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vtpgnebtv) {
  d: path("M8.5 8V5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2v2.5L17 13h-1.5M6 13l2 2l4-4");
}

:global(.y3l9vuvbt) {
  d: path("M4.5 8h9a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-5l-4 3v-3a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2");
}

</style>
