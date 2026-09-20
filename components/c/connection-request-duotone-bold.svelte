<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qhdq2dbof"/><path class="ejfmpibyt"/><path class="fgh6wnb3a"/><path class="a46bghb1i"/><path class="qvtmo6b3b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:connection-request-duotone-bold" {...props}></Icon>
<style>
:global(.a46bghb1i) {
  d: path("M18 10v6");
}

:global(.ejfmpibyt) {
  d: path("M7 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.fgh6wnb3a) {
  d: path("M6 17a4 4 0 0 1 8 0");
}

:global(.qhdq2dbof) {
  fill: currentColor;
  d: path("M7 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qvtmo6b3b) {
  d: path("M15 13h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
