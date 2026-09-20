<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsteb5bse"/><path class="did41pbsp"/><path class="jvpl-4ewk"/><path class="lymn1951z"/><path class="twn25-b-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:measuring-jug-outline-regular" {...props}></Icon>
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

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rsteb5bse) {
  d: path("M5 6v14h10V6");
}

:global(.twn25-b-k) {
  d: path("M6 16h4");
}

</style>
