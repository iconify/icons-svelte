<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fyrlk0i8z"/><path class="untmlqxym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:certification" {...props}></Icon>
<style>
:global(.fyrlk0i8z) {
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.untmlqxym) {
  d: path("m8.75 14.75l-2 6.75l2-1l1.75 1v-6.25m4.75-.5l2 6.75l-2-1l-1.75 1v-6.25M9 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
