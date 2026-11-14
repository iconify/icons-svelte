<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_1f9-bwy"/><path class="iloy6bbio"/><path class="wrz_fn3if"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fiber-patch-panel" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iloy6bbio) {
  d: path("M5.5 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0h.01");
}

:global(.k_1f9-bwy) {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v3a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 10V7A3.5 3.5 0 0 1 6 3.5");
}

:global(.wrz_fn3if) {
  d: path("M13.5 10.5V15c0 4.5-4.5 6.25-9.5 4.25");
}

</style>
