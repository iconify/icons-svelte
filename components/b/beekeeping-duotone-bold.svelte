<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c27-atbzb"/><path class="xktt2fzpr"/><path class="sr_2gtezx"/><path class="bkiaatbvd"/><path class="n75imzbwr"/><path class="jkuojibnm"/><path class="bih55pzif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:beekeeping-duotone-bold" {...props}></Icon>
<style>
:global(.bih55pzif) {
  d: path("M11 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.bkiaatbvd) {
  d: path("M5 5h14v4H5Z");
}

:global(.c27-atbzb) {
  fill: currentColor;
  d: path("M5 5h14v4H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.n75imzbwr) {
  d: path("M5 12h14v4H5Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sr_2gtezx) {
  fill: currentColor;
  d: path("M11 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xktt2fzpr) {
  fill: currentColor;
  d: path("M5 12h14v4H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
