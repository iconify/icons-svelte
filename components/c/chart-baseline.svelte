<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nu5b15shz"/><path class="p8-4cab4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-baseline" {...props}></Icon>
<style>
:global(.nu5b15shz) {
  fill: currentColor;
  d: path("M2.5 11h19v2h-19Z");
}

:global(.p8-4cab4c) {
  d: path("M2.5 8c3-5.5 6-5.5 7.5 0s2.5 13.5 5.5 13.5s4-5.5 6-6.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
