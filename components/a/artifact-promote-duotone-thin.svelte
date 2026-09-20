<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vws5wpblq"/><path class="i43uzzbnk"/><path class="x_r014yat"/><path class="ri2m-q_tv"/><path class="y5493mbgk"/><path class="ae0h5kb0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:artifact-promote-duotone-thin" {...props}></Icon>
<style>
:global(.ae0h5kb0o) {
  d: path("M9 15h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i43uzzbnk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 11.5 12 9l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ri2m-q_tv) {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

:global(.vws5wpblq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x_r014yat) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y5493mbgk) {
  d: path("M9.5 11.5 12 9l2.5 2.5");
}

</style>
