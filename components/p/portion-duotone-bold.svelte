<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="trirghiqk"/><path class="lm0rdp4mt"/><path class="o9nm0ibif"/><path class="mqtixbwqo"/><path class="bso0bbbqi"/><path class="z8g2jgblp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:portion-duotone-bold" {...props}></Icon>
<style>
:global(.bso0bbbqi) {
  d: path("M21 8A9 9 0 0 1 3 8");
}

:global(.lm0rdp4mt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 8A9 9 0 0 1 3 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.o9nm0ibif) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.trirghiqk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z8g2jgblp) {
  d: path("M5 12h14");
}

</style>
