<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y884sf7ga"/><path class="x8vht4e0n"/><path class="g4amvs9gp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hero-pirate" {...props}></Icon>
<style>
:global(.g4amvs9gp) {
  d: path("m6.5 12.5l5.5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x8vht4e0n) {
  fill: currentColor;
  d: path("M12 13.25a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0Z");
}

:global(.y884sf7ga) {
  d: path("m2.5 9.5l4-5.5L12 6l5.5-2l4 5.5Zm4 0V14a5.5 5.5 0 0 0 11 0V9.5");
}

</style>
