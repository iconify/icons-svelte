<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xq1pi7btv"/><path class="sib4g3mzz"/><path class="jt7d488ke"/><path class="j4nym3cre"/><path class="bmr2oqbjx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:food-chain-outline-bold" {...props}></Icon>
<style>
:global(.bmr2oqbjx) {
  d: path("m14 10 2 -2");
}

:global(.j4nym3cre) {
  d: path("m6 16 2 -2");
}

:global(.jt7d488ke) {
  d: path("M13 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sib4g3mzz) {
  d: path("M7 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.xq1pi7btv) {
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
