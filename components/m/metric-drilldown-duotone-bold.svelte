<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dc7s40ben"/><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="w9sbbjb4w"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="zvg9k5fuv"/><path class="nz5g1fb0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metric-drilldown-duotone-bold" {...props}></Icon>
<style>
:global(.dc7s40ben) {
  fill: currentColor;
  d: path("M9 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dh-nlhghu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nz5g1fb0o) {
  d: path("M11.5 10.5 15 14");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w9sbbjb4w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11.5 10.5 15 14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zvg9k5fuv) {
  d: path("M9 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
