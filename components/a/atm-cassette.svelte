<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sqlv1mbsy"/><path class="ach03-rzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:atm-cassette" {...props}></Icon>
<style>
:global(.ach03-rzq) {
  d: path("M13.5 7a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0M9 16.75h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sqlv1mbsy) {
  d: path("M5.125 12h13.75a2.625 2.625 0 0 1 2.625 2.625v4.25a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875v-4.25A2.625 2.625 0 0 1 5.125 12M4 12V6.5a1 1 0 0 1 1-1h2.5m0 6.5V5a1 1 0 0 1 1-1H11m0 8V3.5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1V12");
}

</style>
