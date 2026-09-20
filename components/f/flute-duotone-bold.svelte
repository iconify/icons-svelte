<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yx5f6pbey"/><path class="wwnijrnro"/><path class="esxx8sbse"/><path class="avyvkw01i"/><path class="kv5nd7zpm"/><path class="lgr612izs"/><path class="swzjdoakn"/><path class="zfnkrabzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flute-duotone-bold" {...props}></Icon>
<style>
:global(.avyvkw01i) {
  fill: currentColor;
  d: path("M14 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.esxx8sbse) {
  fill: currentColor;
  d: path("M11 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kv5nd7zpm) {
  d: path("M3 16 17 2l4 4L7 20Z");
}

:global(.lgr612izs) {
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.swzjdoakn) {
  d: path("M11 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.wwnijrnro) {
  fill: currentColor;
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yx5f6pbey) {
  fill: currentColor;
  d: path("M3 16 17 2l4 4L7 20Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zfnkrabzj) {
  d: path("M14 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
