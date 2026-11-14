<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffyv1eg_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:glasses" {...props}></Icon>
<style>
:global(.ffyv1eg_d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-3-1c1-1 2-1 3 0m-11 1V9m19 5V9");
}

</style>
