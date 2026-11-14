<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lmqu8p5zx"/><path class="m7dyfqbmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-warehouse" {...props}></Icon>
<style>
:global(.lmqu8p5zx) {
  d: path("M2.5 9L12 3.5L21.5 9v12h-19Z");
}

:global(.m7dyfqbmr) {
  d: path("M7 21v-8h10v8M7 17h10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
