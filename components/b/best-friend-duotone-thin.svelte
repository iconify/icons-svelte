<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="br5drbqyu"/><path class="ovtnh7b1i"/><path class="pgh99fbrg"/><path class="n5azl05ks"/><path class="cwioy_h_g"/><path class="xo7ududad"/><path class="nggq41d_a"/><path class="tuc-wpbfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:best-friend-duotone-thin" {...props}></Icon>
<style>
:global(.br5drbqyu) {
  fill: currentColor;
  d: path("M12 11C9 9 6 7 7.5 5 9 3.5 11 4.5 12 6c1 -1.5 3 -2.5 4.5 -1C18 7 15 9 12 11");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.cwioy_h_g) {
  d: path("M4 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n5azl05ks) {
  d: path("M12 11C9 9 6 7 7.5 5 9 3.5 11 4.5 12 6c1 -1.5 3 -2.5 4.5 -1C18 7 15 9 12 11");
}

:global(.nggq41d_a) {
  d: path("M16 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ovtnh7b1i) {
  fill: currentColor;
  d: path("M4 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pgh99fbrg) {
  fill: currentColor;
  d: path("M16 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tuc-wpbfs) {
  d: path("M15 21a3 3 0 0 1 6 0");
}

:global(.xo7ududad) {
  d: path("M3 21a3 3 0 0 1 6 0");
}

</style>
