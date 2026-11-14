<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wga40ac5p"/><path class="i-c6dccrj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:metric-delta-down" {...props}></Icon>
<style>
:global(.i-c6dccrj) {
  d: path("M17 12h4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wga40ac5p) {
  fill: currentColor;
  d: path("M2.5 7h12l-6 10Z");
}

</style>
