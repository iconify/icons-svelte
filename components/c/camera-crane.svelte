<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm-9qfict"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camera-crane" {...props}></Icon>
<style>
:global(.mm-9qfict) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 2.5h5V7h-5ZM4 17l13.5-8.5m-8 5V21M6 21h7M2.5 15.5h3v4h-3Z");
}

</style>
