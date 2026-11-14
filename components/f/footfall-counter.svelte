<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tzg9rjb0p"/><path class="potptnjqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:footfall-counter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.potptnjqz) {
  d: path("M11 4.5h2A1.5 1.5 0 0 1 14.5 6A1.5 1.5 0 0 1 13 7.5h-2A1.5 1.5 0 0 1 9.5 6A1.5 1.5 0 0 1 11 4.5M4 13h3m2.75 0h4.5M17 13h3");
}

:global(.tzg9rjb0p) {
  d: path("M4 21.5v-17h16v17");
}

</style>
