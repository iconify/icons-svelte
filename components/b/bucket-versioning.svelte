<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j3tprc-ht"/><path class="kzdusqbsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bucket-versioning" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j3tprc-ht) {
  d: path("m3 6l2 13.5q.25 1 1.5 1h6.05m4.439-7.674L18 6");
}

:global(.kzdusqbsy) {
  d: path("M3 6a7.5 2.5 0 1 0 15 0A7.5 2.5 0 1 0 3 6m13.75 10l.829-.415a1.5 1.5 0 0 1 1.342 0l.829.415a.839.839 0 0 1 0 1.5l-.829.415a1.5 1.5 0 0 1-1.342 0l-.829-.415a.839.839 0 0 1 0-1.5m-1.5 3.75l3 1.5l3-1.5");
}

</style>
