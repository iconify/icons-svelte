<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n57dydbqj"/><path class="gdpoz1bmb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:person-running" {...props}></Icon>
<style>
:global(.gdpoz1bmb) {
  d: path("m6.5 9.5l3.5-2h3.5l3 3.5l3-1");
}

:global(.n57dydbqj) {
  d: path("M13 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm.5 3.5L11 13l3.5 3l-1.5 5m-2-8l-3 3.5l-3.5-.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
