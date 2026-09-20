<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gtlfk7rgu"/><path class="ytkeeccae"/><path class="jeczbgo1q"/><path class="b5ic9acln"/><path class="x6mmtxx8d"/><path class="khp0b8bxr"/><path class="dm800-bqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:late-interaction-duotone-bold" {...props}></Icon>
<style>
:global(.b5ic9acln) {
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
}

:global(.dm800-bqq) {
  d: path("M14.5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gtlfk7rgu) {
  fill: currentColor;
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jeczbgo1q) {
  fill: currentColor;
  d: path("M14.5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.khp0b8bxr) {
  d: path("M10.5 13h3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x6mmtxx8d) {
  d: path("M7.5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ytkeeccae) {
  fill: currentColor;
  d: path("M7.5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
