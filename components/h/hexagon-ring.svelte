<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbzvr-3ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hexagon-ring" {...props}></Icon>
<style>
:global(.pbzvr-3ae) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 12l4.75-8.25m0 0h9.5m0 0L21.5 12m0 0l-4.75 8.25m0 0h-9.5m0 0L2.5 12");
}

</style>
