<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gxggffoxr"/><path class="iayyfm3kx"/><path class="csagyo24e"/><path class="b-mb83bsl"/><path class="youb8ccbq"/><path class="z9rf4z-yw"/><path class="g-a4wz-fw"/><path class="x_kkpk0ip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ingredient-duotone-bold" {...props}></Icon>
<style>
:global(.b-mb83bsl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 14 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.csagyo24e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 14a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g-a4wz-fw) {
  d: path("M8 14a3 3 0 0 1 6 0");
}

:global(.gxggffoxr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iayyfm3kx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 14a5 5 0 0 1 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x_kkpk0ip) {
  d: path("m16 14 5 -5");
}

:global(.youb8ccbq) {
  d: path("M6 14h10");
}

:global(.z9rf4z-yw) {
  d: path("M16 14a5 5 0 0 1 -10 0");
}

</style>
