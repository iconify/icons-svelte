<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gyhtaq2xk"/><path class="i5_elqbnh"/><path class="ecl_f959t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mountain-hut-sharp" {...props}></Icon>
<style>
:global(.ecl_f959t) {
  d: path("M10.75 21.25v-3h2.5v3");
}

:global(.gyhtaq2xk) {
  d: path("m2.75 16.5l5.5-10l3.25 4.75l2.5-3.5l7.25 9.75");
}

:global(.i5_elqbnh) {
  d: path("M7.5 20.25V16.5l.77-.64l2.96-2.47l.77-.64l.77.64l2.96 2.47l.77.64v4.75h-9z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
