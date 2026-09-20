<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="soutn321k"/><path class="uzkjx1-8e"/><path class="c511t3bab"/><path class="c5ywp_2gk"/><path class="p3uietbjg"/><path class="hppiisbif"/><path class="tj_906bjf"/><path class="l8dn9jbyp"/><path class="w60p31c9m"/><path class="e2nq-yvbg"/><path class="e-3fufbxq"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-balcony-duotone-thin" {...props}></Icon>
<style>
:global(.c511t3bab) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c5ywp_2gk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e-3fufbxq) {
  d: path("M19 15v6");
}

:global(.e2nq-yvbg) {
  d: path("M12 15v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hppiisbif) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.p3uietbjg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.soutn321k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v9h16V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tj_906bjf) {
  d: path("M4 3v9h16V3");
}

:global(.uzkjx1-8e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w60p31c9m) {
  d: path("M5 15v6");
}

</style>
