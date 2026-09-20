<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bhkm33b7x"/><path class="x8_u9-97v"/><path class="zpp3fehhr"/><path class="zuuhu6bzg"/><path class="bod4n0b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plank-outline-bold" {...props}></Icon>
<style>
:global(.bhkm33b7x) {
  d: path("M2 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x8_u9-97v) {
  d: path("m6 8 4 4h10");
}

:global(.zpp3fehhr) {
  d: path("M10 12v3");
}

:global(.zuuhu6bzg) {
  d: path("M6 15h6");
}

</style>
