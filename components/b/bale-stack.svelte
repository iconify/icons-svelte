<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h0zyiibqv"/><path class="frb653b0j"/><path class="rhh4v4bgw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bale-stack" {...props}></Icon>
<style>
:global(.frb653b0j) {
  d: path("M7.25 7.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0m0 6.5a2 2 0 1 1-2 2m11.5-2a2 2 0 1 1-2 2");
}

:global(.h0zyiibqv) {
  d: path("M2.5 16.25a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0m9.5 0a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rhh4v4bgw) {
  d: path("M12 5.75a2 2 0 1 1-2 2");
}

</style>
