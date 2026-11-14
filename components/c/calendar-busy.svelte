<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ohd0sccwi"/><path class="pa_e2wbay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:calendar-busy" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ohd0sccwi) {
  d: path("M7.375 4.5h9.25A4.375 4.375 0 0 1 21 8.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-8.25A4.375 4.375 0 0 1 7.375 4.5M8 2.5v4m8-4v4m-13 3h18");
}

:global(.pa_e2wbay) {
  fill: currentColor;
  d: path("M8 14h8a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 16 17H8a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 8 14");
}

</style>
