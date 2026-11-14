<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="trxlteb6d"/><path class="fvpfwtb1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:astronaut" {...props}></Icon>
<style>
:global(.fvpfwtb1t) {
  d: path("M4 21.5c0-3 2.25-4.75 4.75-5.75m6.5 0c2.5 1 4.75 2.75 4.75 5.75M10.5 6.75h3a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5h-3A2.5 2.5 0 0 1 8 9.25a2.5 2.5 0 0 1 2.5-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.trxlteb6d) {
  d: path("M5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>
