<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u-s9u8vws"/><path class="mf8t3e33n"/><path class="r4a6vbbzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:api-environment" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mf8t3e33n) {
  d: path("M9 5.75L6.75 8L9 10.25m6-4.5L17.25 8L15 10.25M8.75 13h6.5A2.75 2.75 0 0 1 18 15.75a2.75 2.75 0 0 1-2.75 2.75h-6.5A2.75 2.75 0 0 1 6 15.75A2.75 2.75 0 0 1 8.75 13");
}

:global(.r4a6vbbzw) {
  fill: currentColor;
  d: path("M13.75 15.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.u-s9u8vws) {
  d: path("M7.75 2.5h8.5a5.25 5.25 0 0 1 5.25 5.25v8.5a5.25 5.25 0 0 1-5.25 5.25h-8.5a5.25 5.25 0 0 1-5.25-5.25v-8.5A5.25 5.25 0 0 1 7.75 2.5");
}

</style>
