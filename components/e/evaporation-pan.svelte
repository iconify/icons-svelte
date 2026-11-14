<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvbtfsb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:evaporation-pan" {...props}></Icon>
<style>
:global(.gvbtfsb6t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 13.5l1.5 6h16l1.5-6m-18.25 3h17.5M7.5 10.75q-1.5-1.5 0-3t0-3m4.5 6q-1.5-1.5 0-3t0-3m4.5 6q-1.5-1.5 0-3t0-3");
}

</style>
