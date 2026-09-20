<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hiyoc5bih"/><path class="tkhdrzhel"/><path class="um18atgqz"/><path class="kkm03rbxe"/><path class="w-pek8c8r"/><path class="elc06ob4j"/><path class="l0v-b4kbr"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:grounding-duotone-bold" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.elc06ob4j) {
  d: path("M8 8h8");
}

:global(.hiyoc5bih) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 2H5v15h14V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kkm03rbxe) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tkhdrzhel) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.um18atgqz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w-pek8c8r) {
  d: path("M14 2H5v15h14V7");
}

</style>
