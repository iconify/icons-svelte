<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tnm8x3vws"/><path class="a-6aaxb4c"/><path class="wptmod37f"/><path class="o9x6y_bij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:command-duotone-thin" {...props}></Icon>
<style>
:global(.a-6aaxb4c) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 10 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o9x6y_bij) {
  d: path("m9 10 -4 4 4 4");
}

:global(.tnm8x3vws) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 4v10H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wptmod37f) {
  d: path("M21 4v10H5");
}

</style>
