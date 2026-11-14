<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olceb_bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bernoulli-wing" {...props}></Icon>
<style>
:global(.olceb_bjo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17c0-2 5-3.5 10-3c4 .5 7 2.5 8.5 4.5C17 19.5 9 20 5 19.5C3.75 19.25 3 18 3 17m0-5c5-2 11-2 18.5 1.5M12 7V2.5M9.5 5L12 2.5L14.5 5");
}

</style>
