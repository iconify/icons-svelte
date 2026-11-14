<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gom1yvpoe"/><path class="dna3z2pfx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:change-house" {...props}></Icon>
<style>
:global(.dna3z2pfx) {
  d: path("M15.5 18a3 3 0 0 1 6 0Zm1 3h.01m1.99.5h.01m1.99-.5h.01");
}

:global(.gom1yvpoe) {
  d: path("M13.7 21.5H2.5v-19h15v9.8M10 2.5v19M7.5 10v2.5m5-2.5v2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
