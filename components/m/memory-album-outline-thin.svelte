<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uk66x15py"/><path class="wuvisubmw"/><path class="jxgkv6s4q"/><path class="sxbibil-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-album-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jxgkv6s4q) {
  d: path("M11 8v8h6V8Z");
}

:global(.sxbibil-o) {
  d: path("m11 14 2 -2 3 3");
}

:global(.uk66x15py) {
  d: path("M4 3v18h16V3Z");
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

</style>
