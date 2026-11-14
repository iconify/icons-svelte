<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnxp-3b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ai-structured-output" {...props}></Icon>
<style>
:global(.qnxp-3b2n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.5c-2 0-2 1-2 3v3C5.5 11 4.5 12 3 12c1.5 0 2.5 1 2.5 2.5v3c0 2 0 3 2 3m9-17c2 0 2 1 2 3v3c0 1.5 1 2.5 2.5 2.5c-1.5 0-2.5 1-2.5 2.5v3c0 2 0 3-2 3M9 8h6m-6 4h6m-6 4h6");
}

</style>
