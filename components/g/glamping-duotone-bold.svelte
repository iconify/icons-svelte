<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vra1stbnu"/><path class="mv4n16bha"/><path class="i6clenrss"/><path class="ydhsvyjzg"/><path class="hc7fbd-jo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:glamping-duotone-bold" {...props}></Icon>
<style>
:global(.hc7fbd-jo) {
  d: path("M4 19h16");
}

:global(.i6clenrss) {
  d: path("M2 16 12 6l10 10Z");
}

:global(.mv4n16bha) {
  fill: currentColor;
  d: path("m12 10.5 2 2 -2 2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vra1stbnu) {
  fill: currentColor;
  d: path("M2 16 12 6l10 10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ydhsvyjzg) {
  d: path("m12 10.5 2 2 -2 2 -2 -2Z");
}

</style>
