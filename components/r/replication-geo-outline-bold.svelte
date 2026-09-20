<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hj9iwxbta"/><path class="jw66ugylr"/><path class="s994z3b0d"/><path class="c9-0s6xhx"/><path class="olqfcgidt"/><path class="i0wu9pzyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:replication-geo-outline-bold" {...props}></Icon>
<style>
:global(.c9-0s6xhx) {
  d: path("m16 3 2 2 -2 2");
}

:global(.hj9iwxbta) {
  d: path("M2 10a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.i0wu9pzyn) {
  d: path("m8 17 -2 2 2 2");
}

:global(.jw66ugylr) {
  d: path("M14 10a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s994z3b0d) {
  d: path("M6 5h12");
}

</style>
