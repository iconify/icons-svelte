<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qton9kw2t"/><path class="y7uqdfbgj"/><path class="my8ijhbaa"/><path class="aw36cedja"/><path class="w7sxxlcqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:permission-grant-duotone-bold" {...props}></Icon>
<style>
:global(.aw36cedja) {
  d: path("M16 15h5");
}

:global(.my8ijhbaa) {
  d: path("M4 10a4 4 0 0 1 8 0");
}

:global(.qton9kw2t) {
  fill: currentColor;
  d: path("M2 12a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
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

:global(.w7sxxlcqv) {
  d: path("m18 12 3 3 -3 3");
}

:global(.y7uqdfbgj) {
  d: path("M2 12a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
