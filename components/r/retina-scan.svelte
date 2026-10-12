<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c645agyxp"/><circle class="pfpt48slt"/><circle class="h_tsn8bxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:retina-scan" {...props}></Icon>
<style>
:global(.c645agyxp) {
  d: path("M3.75 8V6A2.25 2.25 0 0 1 6 3.75h2m8 0h2A2.25 2.25 0 0 1 20.25 6v2m0 8v2A2.25 2.25 0 0 1 18 20.25h-2m-8 0H6A2.25 2.25 0 0 1 3.75 18v-2");
}

:global(.h_tsn8bxt) {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pfpt48slt) {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
}

</style>
