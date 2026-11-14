<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abi02fbuk"/><path class="q5xyx5bnm"/><path class="dajr0zb4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:energy-transition" {...props}></Icon>
<style>
:global(.abi02fbuk) {
  d: path("M15.75 5.505A7.5 7.5 0 0 1 12 19.5");
}

:global(.dajr0zb4v) {
  d: path("m10 2.5l2 2l-2 2m1.474 2.31l-2.116 2.586A.829.829 0 0 0 10 12.75h.051a1.5 1.5 0 0 1 1.488 1.686l-.039.314a.581.581 0 0 0 1.026.44l2.116-2.586A.829.829 0 0 0 14 11.25h-.051a1.5 1.5 0 0 1-1.488-1.686l.039-.314a.581.581 0 0 0-1.026-.44");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q5xyx5bnm) {
  d: path("m14 17.5l-2 2l2 2m-5.75-3.005A7.5 7.5 0 0 1 12 4.5");
}

</style>
