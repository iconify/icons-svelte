<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rsteb5bse"/><path class="did41pbsp"/><path class="jvpl-4ewk"/><path class="lymn1951z"/><path class="twn25-b-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:measuring-jug-outline-bold" {...props}></Icon>
<style>
:global(.did41pbsp) {
  d: path("m15 7 3 -3");
}

:global(.jvpl-4ewk) {
  d: path("M15 10c4 0 4 6 0 6");
}

:global(.lymn1951z) {
  d: path("M6 12h4");
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

</style>
