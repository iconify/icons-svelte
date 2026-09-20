<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aep_ellef"/><path class="ikhputvuo"/><path class="t_57glb-y"/><path class="ftqzjnb8u"/><path class="bzecsub_a"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:egress-duotone-bold" {...props}></Icon>
<style>
:global(.aep_ellef) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bzecsub_a) {
  d: path("M8 12h12");
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.ikhputvuo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t_57glb-y) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
