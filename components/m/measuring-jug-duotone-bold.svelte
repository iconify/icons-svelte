<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pk4yg3b6a"/><path class="jyrgo9c1z"/><path class="if6p90a7n"/><path class="ujr3us5qo"/><path class="xip8g_bzw"/><path class="rsteb5bse"/><path class="did41pbsp"/><path class="jvpl-4ewk"/><path class="lymn1951z"/><path class="twn25-b-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:measuring-jug-duotone-bold" {...props}></Icon>
<style>
:global(.did41pbsp) {
  d: path("m15 7 3 -3");
}

:global(.if6p90a7n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 10c4 0 4 6 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jvpl-4ewk) {
  d: path("M15 10c4 0 4 6 0 6");
}

:global(.jyrgo9c1z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 7 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lymn1951z) {
  d: path("M6 12h4");
}

:global(.pk4yg3b6a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 6v14h10V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rsteb5bse) {
  d: path("M5 6v14h10V6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.twn25-b-k) {
  d: path("M6 16h4");
}

:global(.ujr3us5qo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xip8g_bzw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
