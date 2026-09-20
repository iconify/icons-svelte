<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kkh8mi1vo"/><path class="iedujiqkb"/><path class="eylqpv51p"/><path class="a-9s6wb0y"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:avalanche-outline-bold" {...props}></Icon>
<style>
:global(.a-9s6wb0y) {
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.eylqpv51p) {
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.iedujiqkb) {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.kkh8mi1vo) {
  d: path("m3 16 8 -8 3 3 5 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
