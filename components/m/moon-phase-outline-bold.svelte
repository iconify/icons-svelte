<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w88m64x8i"/><path class="hba66yqou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:moon-phase-outline-bold" {...props}></Icon>
<style>
:global(.hba66yqou) {
  d: path("M18 7a5 5 0 1 0 0 10 4 4 0 0 1 0 -10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w88m64x8i) {
  d: path("M2 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
