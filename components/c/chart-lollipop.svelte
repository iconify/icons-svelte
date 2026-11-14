<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7v7x1bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-lollipop" {...props}></Icon>
<style>
:global(.f7v7x1bcc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20.5V10m5 10.5V7m5 13.5V13M5 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5-3a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
