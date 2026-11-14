<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n6348pv6p"/><path class="fvxtc4bke"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:butcher-shop" {...props}></Icon>
<style>
:global(.fvxtc4bke) {
  d: path("M7 6.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n6348pv6p) {
  d: path("M7.625 2.5h8.75A2.625 2.625 0 0 1 19 5.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 10.875v-5.75A2.625 2.625 0 0 1 7.625 2.5m6.875 11v6.25a1.75 1.75 0 0 0 3.5 0V13.5");
}

</style>
