<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7u29_nhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dance-ribbon" {...props}></Icon>
<style>
:global(.t7u29_nhw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21l5.5-5.5m0 0c3-3-1.5-6 1-9.5S18 3 18 7.5c0 4-4.5 4.5-3 8.5c1 2.5 4.5 3 6.5 1.5");
}

</style>
