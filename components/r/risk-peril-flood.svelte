<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ezfuhbbdz"/><path class="sub8iw5sv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:risk-peril-flood" {...props}></Icon>
<style>
:global(.ezfuhbbdz) {
  d: path("m12 2.5l9.5 9.5l-9.5 9.5L2.5 12Z");
}

:global(.sub8iw5sv) {
  d: path("M7.5 11a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 3 0m-8 3.5a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 3 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
