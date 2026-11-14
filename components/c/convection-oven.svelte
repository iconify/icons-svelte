<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p5r_a3b2h"/><path class="epudswrfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:convection-oven" {...props}></Icon>
<style>
:global(.epudswrfn) {
  d: path("M12 14.5c-2.25-2-1.5-4.5 0-4.5s2.25 2.5 0 4.5Zm0 0c2.75-1 4.75 1 4 2.25s-3.5.75-4-2.25Zm0 0c-.5 3-3.25 3.5-4 2.25s1.25-3.25 4-2.25Z");
}

:global(.p5r_a3b2h) {
  d: path("M3 3h18v18H3Zm0 4h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
