<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="fnsr3fb6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:digital-compendium" {...props}></Icon>
<style>
:global(.fnsr3fb6d) {
  d: path("m9.474 8.158l2.052.684a1.5 1.5 0 0 0 .948 0l2.052-.684A1.5 1.5 0 0 1 16.5 9.581v4.838a1.5 1.5 0 0 1-1.026 1.423l-3 1a1.5 1.5 0 0 1-.948 0l-3-1A1.5 1.5 0 0 1 7.5 14.419V9.581a1.5 1.5 0 0 1 1.974-1.423M12 9v8");
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
