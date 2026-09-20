<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_ssmh9ez"/><path class="mnv4pvbmf"/><path class="i1hf0mb5m"/><path class="hln-s6a_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:game-spinner-outline-thin" {...props}></Icon>
<style>
:global(.hln-s6a_j) {
  d: path("M12 12H6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i1hf0mb5m) {
  d: path("M15 6h3v3Z");
}

:global(.mnv4pvbmf) {
  d: path("m12 12 6 -6");
}

:global(.o_ssmh9ez) {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

</style>
