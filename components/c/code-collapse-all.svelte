<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jajvgv8ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:code-collapse-all" {...props}></Icon>
<style>
:global(.jajvgv8ww) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5L12 3l5 3.5M7 10l5-3.5l5 3.5m-8.5 3.5l-4 3.75l4 3.75m7-7.5l4 3.75l-4 3.75");
}

</style>
