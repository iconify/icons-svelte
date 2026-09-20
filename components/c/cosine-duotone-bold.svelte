<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mlwueibtu"/><path class="jiw8u-asa"/><path class="mj820nbnu"/><path class="emvotkb4z"/><path class="oifr9zbpt"/><path class="h4houcuor"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cosine-duotone-bold" {...props}></Icon>
<style>
:global(.emvotkb4z) {
  d: path("M4 20 20 4");
}

:global(.h4houcuor) {
  d: path("M4 13a7 7 0 0 1 4.95 2.05");
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mj820nbnu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 13a7 7 0 0 1 4.95 2.05");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mlwueibtu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
