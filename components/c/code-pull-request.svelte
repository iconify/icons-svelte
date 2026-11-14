<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oq-j6euas"/><path class="q-5kbtbee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:code-pull-request" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oq-j6euas) {
  d: path("M6.5 7.75v8.5m11 0V9.5A2.5 2.5 0 0 0 15 7h-3.5");
}

:global(.q-5kbtbee) {
  d: path("M13.5 4.5L11 7l2.5 2.5m-9.25-4a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m0 13a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m11 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
