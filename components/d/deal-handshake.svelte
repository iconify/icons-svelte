<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmydohbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deal-handshake" {...props}></Icon>
<style>
:global(.wmydohbxo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h3v7h-3Zm18.3 7h-2.3V5h3v7h-.3M5.5 6.5l4-2.5H14l4.5 2.5m0 5l-3.498 2.831m-2.236 1.735c-.662.307-1.418.202-2.016-.316L5.5 11.5M14 4l-3.5 4.5m4.25 9.5l2 2L21 15.75");
}

</style>
