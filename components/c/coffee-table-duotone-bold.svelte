<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="trirghiqk"/><path class="rdvmv8b4c"/><path class="u03cdlbzd"/><path class="wtdeoydrz"/><path class="mqtixbwqo"/><path class="yam3-1b2z"/><path class="mei2sobow"/><path class="xmopbdc-t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coffee-table-duotone-bold" {...props}></Icon>
<style>
:global(.mei2sobow) {
  d: path("M19 8v12");
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.rdvmv8b4c) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 8v12");
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

:global(.u03cdlbzd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wtdeoydrz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xmopbdc-t) {
  d: path("M5 15h14");
}

:global(.yam3-1b2z) {
  d: path("M5 8v12");
}

</style>
