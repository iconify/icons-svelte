<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uebhhd02r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hammock-sharp" {...props}></Icon>
<style>
:global(.uebhhd02r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5v17.75m17-17.75v17.75M3.5 7.5L7 11m13.5-3.5L17 11M7 11h10c-1 4-3 5.75-5 5.75S8 15 7 11Z");
}

</style>
