<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ts6qbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cable-car-station" {...props}></Icon>
<style>
:global(.k1ts6qbuv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 5L18 2l3.5 3v16.5h-7V11m-12-7l15 5m-14-.5h7l1 7.5h-9Zm3.5-3v3M3 12h8");
}

</style>
