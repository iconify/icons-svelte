<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m25hqbb9k"/><path class="xbhe_sbgv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bosun-whistle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m25hqbb9k) {
  d: path("M2.5 8H14a6 6 0 1 1-6 6v-3H2.5Z");
}

:global(.xbhe_sbgv) {
  d: path("M15.75 6.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M14 14h.01");
}

</style>
