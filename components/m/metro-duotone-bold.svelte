<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a13vvqbuh"/><path class="efioch1iu"/><path class="lynzzcjsm"/><path class="dznv025mt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metro-duotone-bold" {...props}></Icon>
<style>
:global(.a13vvqbuh) {
  fill: currentColor;
  d: path("M6 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dznv025mt) {
  d: path("M6 14h12");
}

:global(.efioch1iu) {
  d: path("M2 12a10 10 0 0 1 20 0");
}

:global(.lynzzcjsm) {
  d: path("M6 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
