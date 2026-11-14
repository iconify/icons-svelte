<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj2y975em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:laminar-flow" {...props}></Icon>
<style>
:global(.hj2y975em) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9C9 9 13 5 21.5 5m-19 9c6.5 0 10.5-4 19-4m-19 9c6.5 0 10.5-4 19-4");
}

</style>
