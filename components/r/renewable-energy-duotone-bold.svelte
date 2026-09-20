<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n5m_-dbxl"/><path class="ru4yg4kdx"/><path class="z50cotl-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:renewable-energy-duotone-bold" {...props}></Icon>
<style>
:global(.n5m_-dbxl) {
  fill: currentColor;
  d: path("M4 20c0 -9.6 6.4 -16 16 -16 0 9.6 -6.4 16 -16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ru4yg4kdx) {
  d: path("M4 20c0 -9.6 6.4 -16 16 -16 0 9.6 -6.4 16 -16 16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z50cotl-z) {
  d: path("m13 8 -3.5 3.5h3L9 15");
}

</style>
