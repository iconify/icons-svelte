<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g94bczb5s"/><path class="ujzcsac9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pareto-80-20" {...props}></Icon>
<style>
:global(.g94bczb5s) {
  fill: currentColor;
  d: path("M3 8h2.5v13H3Zm5 3h2.5v10H8Zm5 3h2.5v7H13Zm5 2h2.5v5H18Z");
}

:global(.ujzcsac9r) {
  d: path("M4.25 5C8 3.25 13 2.5 20.5 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
