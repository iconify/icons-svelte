<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gva4a5bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:print-tongs" {...props}></Icon>
<style>
:global(.gva4a5bqd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 18l4-15.5h4L18 18M3.75 18h4.5v3.5h-4.5Zm12 0h4.5v3.5h-4.5Z");
}

</style>
