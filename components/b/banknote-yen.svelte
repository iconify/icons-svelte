<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrcg6qhaf"/><path class="jb6h_ccnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:banknote-yen" {...props}></Icon>
<style>
:global(.jb6h_ccnx) {
  d: path("M8.75 7.5L12 11.75l3.25-4.25M12 11.75v4.75m-2.5-3.25h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wrcg6qhaf) {
  d: path("M2.5 4.5h19v15h-19Z");
}

</style>
