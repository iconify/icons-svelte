<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw5k9nb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cfl-bulb" {...props}></Icon>
<style>
:global(.dw5k9nb-h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 14.5v-2h6A2.25 2.25 0 0 0 15 8H9a2.25 2.25 0 0 1 0-4.5h6m-7 11h8V18H8Zm2.5 6.25h3");
}

</style>
