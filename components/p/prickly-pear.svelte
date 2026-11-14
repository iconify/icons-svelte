<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ir_nngbpr"/><path class="ixqpe2b8h"/><path class="hi79qvjxr"/><path class="kkim5ibmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:prickly-pear" {...props}></Icon>
<style>
:global(.hi79qvjxr) {
  fill: currentColor;
  d: path("M17.5 3a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ir_nngbpr) {
  d: path("M8 15.75a4 5.75 0 1 0 8 0a4 5.75 0 1 0-8 0");
}

:global(.ixqpe2b8h) {
  d: path("M13.5 6.5a2.5 4 0 1 0 5 0a2.5 4 0 1 0-5 0m-9.25 3.75a2.25 3.5 0 1 0 4.5 0a2.25 3.5 0 1 0-4.5 0");
}

:global(.kkim5ibmm) {
  d: path("M10.75 14.5h.01m2.49 3.5h.01");
}

</style>
