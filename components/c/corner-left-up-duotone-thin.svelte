<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-f8kachd"/><path class="j3ck4vuoi"/><path class="mwaecstwf"/><path class="p1z08ccdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-left-up-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j3ck4vuoi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 9 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mwaecstwf) {
  d: path("M20 20H10V4");
}

:global(.p1z08ccdv) {
  d: path("m5 9 5 -5 5 5");
}

:global(.x-f8kachd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 20H10V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
