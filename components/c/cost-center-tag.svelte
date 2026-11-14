<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bhoryjedw"/><path class="pf1bxnv-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cost-center-tag" {...props}></Icon>
<style>
:global(.bhoryjedw) {
  d: path("M9.793 5.5h8.082A2.625 2.625 0 0 1 20.5 8.125v7.75a2.625 2.625 0 0 1-2.625 2.625H9.793a2.63 2.63 0 0 1-2.081-1.025L4.731 13.6a2.625 2.625 0 0 1 0-3.2l2.981-3.875A2.63 2.63 0 0 1 9.793 5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pf1bxnv-c) {
  d: path("M7 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.75 0H17");
}

</style>
