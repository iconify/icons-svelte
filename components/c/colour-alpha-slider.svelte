<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv8ggs65g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:colour-alpha-slider" {...props}></Icon>
<style>
:global(.qv8ggs65g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h6v6h-6Zm3 0v6m-3-3h6m2.75 0h2.5m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5 0h2.75");
}

</style>
