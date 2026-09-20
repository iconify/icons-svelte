<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zicgvsboo"/><path class="afnfsddeu"/><path class="wj8ybccjk"/><path class="t_rstj6cq"/><path class="jfpn1_rdc"/><path class="w74_pkbuu"/><path class="nj-oiubfo"/><path class="r7xk8o29f"/><path class="sunqexbsa"/><path class="om2raabrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:audio-duotone-thin" {...props}></Icon>
<style>
:global(.afnfsddeu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jfpn1_rdc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nj-oiubfo) {
  d: path("M8 7v10");
}

:global(.om2raabrv) {
  d: path("M20 10v4");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.sunqexbsa) {
  d: path("M16 7v10");
}

:global(.t_rstj6cq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w74_pkbuu) {
  d: path("M4 10v4");
}

:global(.wj8ybccjk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zicgvsboo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
