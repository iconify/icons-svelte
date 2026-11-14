<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rur0mzb4g"/><path class="m_-aexz3a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:forward-10" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m_-aexz3a) {
  d: path("m9 2.5l3 3l-3 3m-.5 3l1-1v5m4.75-5zA1.75 1.75 0 0 1 16 12.25v1.5a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75v-1.5a1.75 1.75 0 0 1 1.75-1.75");
}

:global(.rur0mzb4g) {
  d: path("M18.495 9.25A7.5 7.5 0 1 1 12 5.5");
}

</style>
