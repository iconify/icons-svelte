<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jpzm84ifn"/><path class="z9w5pkqbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-merge-right" {...props}></Icon>
<style>
:global(.jpzm84ifn) {
  d: path("m3 6l7 6h11M3 18l7-6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z9w5pkqbx) {
  d: path("M17.5 8.5L21 12l-3.5 3.5");
}

</style>
