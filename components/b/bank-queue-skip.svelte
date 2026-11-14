<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rq88v3bnp"/><path class="n4_dx8isk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bank-queue-skip" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n4_dx8isk) {
  d: path("M18.5 13.75L21 16l.75-3.25M6 19.5h.01m5.99 0h.01m5.99 0h.01");
}

:global(.rq88v3bnp) {
  d: path("M3 16C4.5 5.5 19.5 5.5 21 16");
}

</style>
