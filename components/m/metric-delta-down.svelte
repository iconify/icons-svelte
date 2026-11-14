<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lkh49gzer"/><path class="i-c6dccrj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:metric-delta-down" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i-c6dccrj) {
  d: path("M17 12h4.5");
}

:global(.lkh49gzer) {
  fill: currentColor;
  d: path("M5.591 7h5.818a1.75 1.75 0 0 1 1.501 2.65l-2.909 4.849a1.75 1.75 0 0 1-3.002 0L4.09 9.65A1.75 1.75 0 0 1 5.591 7");
}

</style>
