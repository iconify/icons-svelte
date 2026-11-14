<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6xfakbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bocce" {...props}></Icon>
<style>
:global(.y6xfakbmr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm11 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM8.5 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

</style>
