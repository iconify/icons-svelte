<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdxypjb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fast-food-restaurant" {...props}></Icon>
<style>
:global(.sdxypjb9t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14a4.75 4.75 0 0 1 9.5 0Zm0 3H12v4H2.5Zm12.25-7h6.75l-1 11h-4.75Zm2 0V4.5M19.5 10V5.5");
}

</style>
