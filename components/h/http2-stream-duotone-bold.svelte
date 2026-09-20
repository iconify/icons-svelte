<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xc-pw4ble"/><path class="unjh48car"/><path class="zdx90xb1o"/><path class="z8g2jgblp"/><path class="jxfqwcbwg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:http2-stream-duotone-bold" {...props}></Icon>
<style>
:global(.jxfqwcbwg) {
  d: path("M5 14.5h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.unjh48car) {
  d: path("M2 12a5 5 0 0 1 5 -5h10a5 5 0 0 1 5 5 5 5 0 0 1 -5 5H7a5 5 0 0 1 -5 -5");
}

:global(.xc-pw4ble) {
  fill: currentColor;
  d: path("M2 12a5 5 0 0 1 5 -5h10a5 5 0 0 1 5 5 5 5 0 0 1 -5 5H7a5 5 0 0 1 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.z8g2jgblp) {
  d: path("M5 12h14");
}

:global(.zdx90xb1o) {
  d: path("M5 9.5h14");
}

</style>
