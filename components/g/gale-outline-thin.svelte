<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c5ipzfbmx"/><path class="d8abqfbpc"/><path class="fu2iodbya"/><path class="r_-onzaex"/><path class="gv9l4p83m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gale-outline-thin" {...props}></Icon>
<style>
:global(.c5ipzfbmx) {
  d: path("M3 6h16");
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.fu2iodbya) {
  d: path("M3 16h16");
}

:global(.gv9l4p83m) {
  d: path("m21 19 -3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r_-onzaex) {
  d: path("m16 19 -3 3");
}

</style>
