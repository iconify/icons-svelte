<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk99dhbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:groomed-slope" {...props}></Icon>
<style>
:global(.fk99dhbwr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5C5 8 8.5 4.5 12 4.5s7 3.5 9.5 15M13 9l3 6.5m-6.5-5l3 6.5M7 15l1.5 3.5");
}

</style>
