<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="amfjlc-na"/><path class="h7eigqbck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camp-string-lights" {...props}></Icon>
<style>
:global(.amfjlc-na) {
  d: path("M2.5 4v17m19-17v17M2.5 5q9.5 10 19 0");
}

:global(.h7eigqbck) {
  d: path("M5 9.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.5 1.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM16 9.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
