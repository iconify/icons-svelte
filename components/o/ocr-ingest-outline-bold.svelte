<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w-0ktubui"/><path class="yxcg20bta"/><path class="c0_odobsd"/><path class="gvfa1mb1f"/><path class="qhy91zm_e"/><path class="okzo6wb9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ocr-ingest-outline-bold" {...props}></Icon>
<style>
:global(.c0_odobsd) {
  d: path("M3 17v3h3");
}

:global(.gvfa1mb1f) {
  d: path("M11 20h3v-3");
}

:global(.okzo6wb9p) {
  d: path("m17 10 2 2 -2 2");
}

:global(.qhy91zm_e) {
  d: path("M6 12h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w-0ktubui) {
  d: path("M3 7V4h3");
}

:global(.yxcg20bta) {
  d: path("M11 4h3v3");
}

</style>
