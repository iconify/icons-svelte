<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c8vzhqb-a"/><path class="f0r-gub1r"/><path class="sxbsk4rmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:code-copy" {...props}></Icon>
<style>
:global(.c8vzhqb-a) {
  d: path("M2.5 13V4.5a2 2 0 0 1 2-2H13");
}

:global(.f0r-gub1r) {
  d: path("M10 6.5h8a3.5 3.5 0 0 1 3.5 3.5v8a3.5 3.5 0 0 1-3.5 3.5h-8A3.5 3.5 0 0 1 6.5 18v-8A3.5 3.5 0 0 1 10 6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sxbsk4rmu) {
  d: path("m12 11l-2.5 3l2.5 3m4-6l2.5 3l-2.5 3");
}

</style>
