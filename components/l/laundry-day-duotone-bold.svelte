<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ded97twic"/><path class="b-lvfgzhu"/><path class="r13_5uqbr"/><path class="kamdbib6v"/><path class="pqojzri_o"/><path class="sno-u_b6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:laundry-day-duotone-bold" {...props}></Icon>
<style>
:global(.b-lvfgzhu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7v7h4V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ded97twic) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.pqojzri_o) {
  d: path("M6 7v7h4V7");
}

:global(.r13_5uqbr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 7v10h4V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sno-u_b6h) {
  d: path("M14 7v10h4V7");
}

</style>
