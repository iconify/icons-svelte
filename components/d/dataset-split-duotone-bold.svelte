<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cvoep2bmy"/><path class="zrwkhybyf"/><path class="s7eyaw7qq"/><path class="nzatmusii"/><path class="wg8_ddc1f"/><path class="zuuhu6bzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dataset-split-duotone-bold" {...props}></Icon>
<style>
:global(.cvoep2bmy) {
  fill: currentColor;
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nzatmusii) {
  d: path("M6 9h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s7eyaw7qq) {
  d: path("M15 4v16");
}

:global(.wg8_ddc1f) {
  d: path("M6 12h6");
}

:global(.zrwkhybyf) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.zuuhu6bzg) {
  d: path("M6 15h6");
}

</style>
