<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c30uksb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:c-stand" {...props}></Icon>
<style>
:global(.c30uksb0b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 4.5v17m0-6l-4.5 6m4.5-6l4.5 6M8 8h3.5m0 0a5 5 0 1 0 10 0a5 5 0 1 0-10 0M8 8h.01");
}

</style>
