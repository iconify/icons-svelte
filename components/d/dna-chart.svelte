<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oidxa-2ga"/><path class="cm2ow8cxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dna-chart" {...props}></Icon>
<style>
:global(.cm2ow8cxc) {
  d: path("M13 2.5C13 7.25 3 7.25 3 12c0 4.302 8.201 4.708 9.75 8.274M3 12h10m2.5 9.5v-3m3 3v-5m3 5v-7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oidxa-2ga) {
  d: path("M3 2.5C3 7.25 13 7.25 13 12S3 16.75 3 21.5");
}

</style>
