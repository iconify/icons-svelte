<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ax5-ftkkw"/><path class="wry_o9rmj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:alarm-clock-check" {...props}></Icon>
<style>
:global(.ax5-ftkkw) {
  d: path("M4.5 13a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0M3 6l3-3m15 3l-3-3M6.5 18.5l-2 2m13-2l2 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wry_o9rmj) {
  d: path("m9 13.25l2 2l4-4");
}

</style>
