<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tuq82lbhh"/><path class="w80whxt-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:file-py" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tuq82lbhh) {
  d: path("M4.5 12V5A2.5 2.5 0 0 1 7 2.5h6.5l6 6V12");
}

:global(.w80whxt-s) {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M6 21.5v-6h2.5a2 2 0 0 1 0 4H6m7.5-4l2.5 3l2.5-3m-2.5 3v3");
}

</style>
