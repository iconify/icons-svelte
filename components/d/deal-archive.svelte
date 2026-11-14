<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su69-c5er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deal-archive" {...props}></Icon>
<style>
:global(.su69-c5er) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h18V8H3ZM4.5 8v9A1.5 1.5 0 0 0 6 18.5h12a1.5 1.5 0 0 0 1.5-1.5V8m-17 13.5h19m-12-9h5");
}

</style>
