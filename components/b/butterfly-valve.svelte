<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lik8a3bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:butterfly-valve" {...props}></Icon>
<style>
:global(.lik8a3bfw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0ZM2 9.5h5m-5 5h5m10-5h5m-5 5h5M8.5 3.5h7m-3.5 0v3m-1.75 7.25l3.5-3.5");
}

</style>
