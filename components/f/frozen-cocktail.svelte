<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7l_0y85q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:frozen-cocktail" {...props}></Icon>
<style>
:global(.w7l_0y85q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11h14a7 5.5 0 0 1-14 0m.5 0A3 3 0 0 1 8 7a4 4 0 0 1 8 0a3 3 0 0 1 2.5 4M12 16.5v4m-3.5 0h7");
}

</style>
