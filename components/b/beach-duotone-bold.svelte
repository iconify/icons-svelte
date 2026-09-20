<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i05-3-p3f"/><path class="itcs4-8rc"/><path class="keeez031w"/><path class="tee5ti87r"/><path class="nqnw98byf"/><path class="olqfcgidt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:beach-duotone-bold" {...props}></Icon>
<style>
:global(.i05-3-p3f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 9 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.itcs4-8rc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.keeez031w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nqnw98byf) {
  d: path("M2 14h20");
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tee5ti87r) {
  d: path("m3 9 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>
