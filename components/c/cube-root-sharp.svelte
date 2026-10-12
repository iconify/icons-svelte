<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uiywbk0ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cube-root-sharp" {...props}></Icon>
<style>
:global(.uiywbk0ie) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15h2.5L9 20.25l5-16.5h7.25m-17.75 0h3.25L5 6.25h2.25v3.5H4l-.5-.5");
}

</style>
