<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="unjh48car"/><path class="zdx90xb1o"/><path class="z8g2jgblp"/><path class="jxfqwcbwg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:http2-stream-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jxfqwcbwg) {
  d: path("M5 14.5h14");
}

:global(.unjh48car) {
  d: path("M2 12a5 5 0 0 1 5 -5h10a5 5 0 0 1 5 5 5 5 0 0 1 -5 5H7a5 5 0 0 1 -5 -5");
}

:global(.z8g2jgblp) {
  d: path("M5 12h14");
}

:global(.zdx90xb1o) {
  d: path("M5 9.5h14");
}

</style>
