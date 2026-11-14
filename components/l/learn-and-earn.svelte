<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlke_lbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:learn-and-earn" {...props}></Icon>
<style>
:global(.wlke_lbeo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2l9 4.25l-9 4.25l-9-4.25Zm9 4.25v4.25m-13 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4 0h.01");
}

</style>
