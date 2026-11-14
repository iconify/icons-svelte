<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7j5edcbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:champagne-saber" {...props}></Icon>
<style>
:global(.t7j5edcbh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12h7c2 0 3 2 5 2h4v3h-4c-2 0-3 2-5 2h-7a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2ZM6 6l12.5 5.5M5 8.25l2-4.5M6 6L2.5 4.5");
}

</style>
