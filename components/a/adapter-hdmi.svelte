<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cccmi1bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:adapter-hdmi" {...props}></Icon>
<style>
:global(.cccmi1bwg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4h17v4.5L17 12H7L3.5 8.5ZM8 12h8l-1 4.5H9Zm4 4.5v5M7.5 7h9");
}

</style>
