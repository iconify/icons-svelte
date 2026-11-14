<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="liqqgwj2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:orchard-ladder" {...props}></Icon>
<style>
:global(.liqqgwj2i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21.5L9 3.5h2l1.5 18M11 3.5l8.5 18m-12-12h4m-5.5 6h6");
}

</style>
