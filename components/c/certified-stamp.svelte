<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="trxlteb6d"/><path class="a-8dcmblb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:certified-stamp" {...props}></Icon>
<style>
:global(.a-8dcmblb) {
  d: path("M7.75 15v6L9 19.75L10.25 21v-4.75m3.5 0V21L15 19.75L16.25 21v-6m-7.5-5.25L11 12l4.25-4.5");
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
