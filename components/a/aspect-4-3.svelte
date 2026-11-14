<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="onw8lwggl"/><path class="dtdcglbfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:aspect-4-3" {...props}></Icon>
<style>
:global(.dtdcglbfe) {
  d: path("M6 10.5V8h2.5m7 0H18v2.5m0 3V16h-2.5m-7 0H6v-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.onw8lwggl) {
  d: path("M6.5 5.25h11a3.5 3.5 0 0 1 3.5 3.5v6.5a3.5 3.5 0 0 1-3.5 3.5h-11a3.5 3.5 0 0 1-3.5-3.5v-6.5a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
