<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dsh6t34ve"/><path class="k187sabpz"/><path class="f8208jb9b"/><path class="mhk3euagx"/><path class="brz3--krt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:martial-arts-duotone-thin" {...props}></Icon>
<style>
:global(.brz3--krt) {
  d: path("m15 14 4 4");
}

:global(.dsh6t34ve) {
  fill: currentColor;
  d: path("M9 8v6h6V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f8208jb9b) {
  d: path("M9 8v6h6V8Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k187sabpz) {
  d: path("M2 11h20");
}

:global(.mhk3euagx) {
  d: path("m9 14 -4 4");
}

</style>
