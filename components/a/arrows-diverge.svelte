<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jqpc1_rmu"/><path class="uxp-y7btg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrows-diverge" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jqpc1_rmu) {
  d: path("M3.75 12h5c3.5 0 4.25-6 8-6H20M8.75 12c3.5 0 4.25 6 8 6H20");
}

:global(.uxp-y7btg) {
  d: path("m17.25 3l3 3l-3 3m0 6l3 3l-3 3");
}

</style>
