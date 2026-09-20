<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uk66x15py"/><path class="wuvisubmw"/><path class="jxgkv6s4q"/><path class="sxbibil-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-album-outline-bold" {...props}></Icon>
<style>
:global(.jxgkv6s4q) {
  d: path("M11 8v8h6V8Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
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
