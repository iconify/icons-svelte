<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="dr4punj1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:airport-diagram" {...props}></Icon>
<style>
:global(.dr4punj1b) {
  d: path("M9 6h6a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 15 9H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 6m0 9h6a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 15 18H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 15m1-6l4 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o72zbacef) {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5");
}

</style>
