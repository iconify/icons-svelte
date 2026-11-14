<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kld60abhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mouse-scroll" {...props}></Icon>
<style>
:global(.kld60abhb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h4a3.5 3.5 0 0 1 3.5 3.5v11A3.5 3.5 0 0 1 11 21H7a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 7 3Zm2 3.5v3M17.5 8L19 6.5L20.5 8m-3 5l1.5 1.5l1.5-1.5");
}

</style>
