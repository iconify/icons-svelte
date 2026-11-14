<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jgiaaebje"/><path class="pujnq4_bn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ape-skull" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jgiaaebje) {
  d: path("M3.5 9.5C6 5 9.5 3 14 3s7 3.5 7 7.5q0 4.5-4.5 6l-1.5 4H8.5L3 17l2.5-4.5Z");
}

:global(.pujnq4_bn) {
  d: path("M8 10.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
