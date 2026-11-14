<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0f2705vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cordless-drill" {...props}></Icon>
<style>
:global(.c0f2705vc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h13v7H3ZM16 5h2.5v4H16Zm2.5 2h3m-15 3.5L6 16m5-5.5l-.5 5.5m-7 0h10v5h-10Z");
}

</style>
