<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k15q4tbdt"/><path class="z9ittvbis"/><path class="bnhdslb0j"/><path class="vl804rbny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dawn-outline-bold" {...props}></Icon>
<style>
:global(.bnhdslb0j) {
  d: path("M19 8v6");
}

:global(.k15q4tbdt) {
  d: path("M6 19a6 6 0 0 1 12 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vl804rbny) {
  d: path("M16.5 10.5 19 8l2.5 2.5");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
