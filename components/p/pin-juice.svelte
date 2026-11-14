<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyv78jpyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-juice" {...props}></Icon>
<style>
:global(.lyv78jpyc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h12l-1.5 16a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 20Zm.5 5.5h11m-6.5 7l4-14");
}

</style>
