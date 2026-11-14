<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h8rcv7zsu"/><path class="fwbauwbme"/><path class="i7doc9bbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rock-garden" {...props}></Icon>
<style>
:global(.fwbauwbme) {
  d: path("M6.5 11.5a5.5 2.5 0 1 0 11 0a5.5 2.5 0 1 0-11 0");
}

:global(.h8rcv7zsu) {
  d: path("M4 17a8 3 0 1 0 16 0a8 3 0 1 0-16 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i7doc9bbg) {
  d: path("M8.25 6.75a3.75 2.25 0 1 0 7.5 0a3.75 2.25 0 1 0-7.5 0");
}

</style>
