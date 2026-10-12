<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fti7nl0tw"/><path class="i0iuipxhm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-turn-up-sharp" {...props}></Icon>
<style>
:global(.fti7nl0tw) {
  d: path("M6.25 19.75a8 8 0 0 0 8-8v-7");
}

:global(.i0iuipxhm) {
  d: path("m10.5 8.5l3.75-3.75L18 8.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
