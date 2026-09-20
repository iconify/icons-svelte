<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ugdbidcqi"/><path class="l2xj1bblk"/><path class="u8ebpfbzk"/><path class="rrzohjbez"/><path class="jlojnsdlu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:help-outline-regular" {...props}></Icon>
<style>
:global(.jlojnsdlu) {
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.l2xj1bblk) {
  d: path("M9 9a3 3 0 0 1 6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rrzohjbez) {
  d: path("M12 12v3");
}

:global(.u8ebpfbzk) {
  d: path("m15 9 -3 3");
}

:global(.ugdbidcqi) {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

</style>
