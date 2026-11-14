<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tk0mugt8p"/><path class="xjmx68i3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:aspect-ratio-lock" {...props}></Icon>
<style>
:global(.tk0mugt8p) {
  d: path("M11.7 18.5H2.5v-16h16v7.7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xjmx68i3d) {
  d: path("M6 10V6h4m4.5 10.5H22V22h-7.5Zm1.75 0V15a2 2 0 0 1 4 0v1.5");
}

</style>
