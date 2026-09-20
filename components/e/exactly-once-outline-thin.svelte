<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jlt4pubuu"/><path class="iedujiqkb"/><path class="fotxf46ll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exactly-once-outline-thin" {...props}></Icon>
<style>
:global(.fotxf46ll) {
  d: path("m14 12.5 3 3 4.5 -4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iedujiqkb) {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jlt4pubuu) {
  d: path("M4 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
