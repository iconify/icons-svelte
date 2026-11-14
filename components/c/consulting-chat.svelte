<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fxnk-y7ax"/><path class="cvpz47bqv"/><path class="uxq2lubxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:consulting-chat" {...props}></Icon>
<style>
:global(.cvpz47bqv) {
  d: path("M5 6h8.5A2.5 2.5 0 0 1 16 8.5v12l-2.75-2H5A2.5 2.5 0 0 1 2.5 16V8.5A2.5 2.5 0 0 1 5 6");
}

:global(.fxnk-y7ax) {
  d: path("M8.5 6V4.5a2 2 0 0 1 2-2h8A2.5 2.5 0 0 1 21 5v10.5l-2.5-2H16");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uxq2lubxb) {
  d: path("M7.5 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-1.75 8a3.5 3.5 0 0 1 7 0");
}

</style>
