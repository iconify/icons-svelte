<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="csk2xcisd"/><path class="cfjh0bb9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:drone-battery" {...props}></Icon>
<style>
:global(.cfjh0bb9c) {
  d: path("m12 12.5l-2.25 2.25H13L10.75 17");
}

:global(.csk2xcisd) {
  d: path("M6.875 9.75h7.75A4.375 4.375 0 0 1 19 14.125v1.25a4.375 4.375 0 0 1-4.375 4.375h-7.75A4.375 4.375 0 0 1 2.5 15.375v-1.25A4.375 4.375 0 0 1 6.875 9.75M21.75 13.5V16M2.5 4.5a3.25 1.5 0 1 0 6.5 0a3.25 1.5 0 1 0-6.5 0m10 0a3.25 1.5 0 1 0 6.5 0a3.25 1.5 0 1 0-6.5 0M5.75 6v3.75m10-3.75v3.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
