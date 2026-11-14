<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsby-ebar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cell-tower-guyed" {...props}></Icon>
<style>
:global(.hsby-ebar) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21V2.5h3V21m-3-13l3 4.5l-3 4.5M3 21l7.5-13M7 21l3.5-4M21 21L13.5 5m4 16l-4-8.5");
}

</style>
