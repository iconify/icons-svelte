<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldtt98bnr"/><path class="ol_fl_z0k"/><path class="rwlmyhbeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:penthouse" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ldtt98bnr) {
  d: path("M5 8v13.5h14V8");
}

:global(.ol_fl_z0k) {
  fill: currentColor;
  d: path("M4.75 3.5h14.5A1.75 1.75 0 0 1 21 5.25v1A1.75 1.75 0 0 1 19.25 8H4.75A1.75 1.75 0 0 1 3 6.25v-1A1.75 1.75 0 0 1 4.75 3.5");
}

:global(.rwlmyhbeb) {
  d: path("M8 11.5h1.5m5 0H16M8 15h1.5m5 0H16m-5.5 6.5v-3h3v3");
}

</style>
