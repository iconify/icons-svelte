<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hg_gmpbba"/><path class="c5b24hbya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:autofocus-sharp" {...props}></Icon>
<style>
:global(.c5b24hbya) {
  d: path("m8.5 14.25l1.75-4.5l1.75 4.5m-2.9-1.5h2.3m2.6 1.5v-4.5h2M14 12h1.5");
}

:global(.hg_gmpbba) {
  d: path("M2.75 7.75v-5h5m8.5 0h5v5m0 8.5v5h-5m-8.5 0h-5v-5M6 7.5h12v9H6z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
