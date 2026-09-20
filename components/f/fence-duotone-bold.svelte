<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w6akctrde"/><path class="x2dc1dsim"/><path class="mf1nsbben"/><path class="zaep_nbcg"/><path class="e8db_cbso"/><path class="s_uvnuivb"/><path class="uhty14kih"/><path class="f50v0cimy"/><path class="v5d935don"/><path class="ef5tcc6_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fence-duotone-bold" {...props}></Icon>
<style>
:global(.e8db_cbso) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ef5tcc6_c) {
  d: path("M4 16h14");
}

:global(.f50v0cimy) {
  d: path("M18 7v14");
}

:global(.mf1nsbben) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s_uvnuivb) {
  d: path("M4 7v14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uhty14kih) {
  d: path("M11 7v14");
}

:global(.v5d935don) {
  d: path("M4 11h14");
}

:global(.w6akctrde) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x2dc1dsim) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zaep_nbcg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
