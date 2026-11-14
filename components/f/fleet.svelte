<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mve7j4bks"/><path class="zm9qeexje"/><path class="tjx7wcbku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fleet" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mve7j4bks) {
  d: path("M3.5 16V4.5A1.5 1.5 0 0 1 5 3h7.5");
}

:global(.tjx7wcbku) {
  d: path("M7.5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.zm9qeexje) {
  d: path("M6.5 17V7.5a1 1 0 0 1 1-1h7V10h3l3 3v4Z");
}

</style>
