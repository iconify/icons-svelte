<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ezfuhbbdz"/><path class="rch1tfw0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:risk-peril-fire" {...props}></Icon>
<style>
:global(.ezfuhbbdz) {
  d: path("m12 2.5l9.5 9.5l-9.5 9.5L2.5 12Z");
}

:global(.rch1tfw0w) {
  d: path("M12 17c-1.75 0-2.75-1-2.75-2.25c0-1.5 1.75-2 2-3.75c.75.5 1 1.25 1 2c.75-.25 1.25-1 1.5-1.5c.75 1 1 2 1 3.25S13.75 17 12 17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
