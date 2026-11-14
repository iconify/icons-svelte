<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ex2jlbb_w"/><path class="ojydkkbir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:editing-marks" {...props}></Icon>
<style>
:global(.ex2jlbb_w) {
  d: path("M7 2.5h7A3.5 3.5 0 0 1 17.5 6v12a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V6A3.5 3.5 0 0 1 7 2.5M7 8h14M6.5 13.5h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ojydkkbir) {
  d: path("m7 18.75l2.5-2.5l2.5 2.5");
}

</style>
