<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a9qmb2b7h"/><path class="bt2ootzqw"/><path class="ngs276d9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:enum" {...props}></Icon>
<style>
:global(.a9qmb2b7h) {
  d: path("M3 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.bt2ootzqw) {
  fill: currentColor;
  d: path("M3 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ngs276d9d) {
  d: path("M3 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7-14h11m-11 7h11m-11 7h11");
}

</style>
