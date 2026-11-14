<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8h_3tb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:precision-dots" {...props}></Icon>
<style>
:global(.b8h_3tb6h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4h.01M12 4h.01M20 4h.01M4 12h.01M20 12h.01M4 20h.01M12 20h.01M20 20h.01M12 8.5v7M8.5 12h7");
}

</style>
