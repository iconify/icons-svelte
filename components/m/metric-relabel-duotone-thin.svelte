<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v72ku2b4z"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="gffdk79ec"/><path class="wb770htsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metric-relabel-duotone-thin" {...props}></Icon>
<style>
:global(.gffdk79ec) {
  d: path("M9 8h3l3 3 -3 3H9Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.v72ku2b4z) {
  fill: currentColor;
  d: path("M9 8h3l3 3 -3 3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wb770htsg) {
  d: path("m8.5 14.5 7 -7");
}

</style>
