<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i49zxtdns"/><path class="tcwtwdj_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:deposit-refund" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i49zxtdns) {
  d: path("M6.5 17.25c-2.25-2.75-1-7 2.25-9.75c3.5-2.75 7.75-3.25 10-.5c1.5 1.75 1.75 3.75.5 6L21 15l-2 1.5l-1-1.25l-1.5 1.5c-.5.5-1 .75-1.75 1l1.25 1.5l-2 1.5l-1.5-2q-3.75 1.125-6-1.5");
}

:global(.tcwtwdj_v) {
  d: path("M6 15.75L4.5 17l1.75 2.25L8 18m.5-4h.01m.74-3.5l2.25-2M3.25 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
