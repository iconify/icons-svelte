<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dldih4b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:friend-request-game" {...props}></Icon>
<style>
:global(.dldih4b6r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM3 21.5v-1C3 17 6 15 10 15c.746 0 1.491.089 2.184.267M18.5 14v7M15 17.5h7");
}

</style>
