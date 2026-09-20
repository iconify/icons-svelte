<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_2z93bzc"/><path class="l65brscyv"/><path class="rsu38odap"/><path class="jeb_6eb2t"/><path class="dx99bfbil"/><path class="hspeesv2z"/><path class="ujt25lh2u"/><path class="tv6hbrcra"/><path class="u0f6w1z_e"/><path class="n3p0zmbop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:goal-at-risk-duotone-thin" {...props}></Icon>
<style>
:global(.dx99bfbil) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hspeesv2z) {
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
}

:global(.jeb_6eb2t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 20.5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k_2z93bzc) {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l65brscyv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.rsu38odap) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 15v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tv6hbrcra) {
  d: path("M8.5 20.5h7");
}

:global(.u0f6w1z_e) {
  d: path("M12 6v3");
}

:global(.ujt25lh2u) {
  d: path("M12 15v5.5");
}

</style>
