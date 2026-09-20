<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vws5wpblq"/><path class="shlqptb2b"/><path class="g9gc9wboi"/><path class="ke9b-u_dj"/><path class="ri2m-q_tv"/><path class="e3dlplb2a"/><path class="gyrsppg8d"/><path class="g45hqpb0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:deploy-window-duotone-thin" {...props}></Icon>
<style>
:global(.e3dlplb2a) {
  d: path("M10.5 9H8v6h2.5");
}

:global(.g45hqpb0s) {
  d: path("M10.5 12h3");
}

:global(.g9gc9wboi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 9H16v6h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gyrsppg8d) {
  d: path("M13.5 9H16v6h-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ke9b-u_dj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ri2m-q_tv) {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

:global(.shlqptb2b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 9H8v6h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vws5wpblq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
