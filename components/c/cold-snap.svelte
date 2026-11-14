<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv1vpxb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cold-snap" {...props}></Icon>
<style>
:global(.kv1vpxb9t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13V5.5a3 3 0 0 1 6 0V13a5 5 0 1 1-6 0M18.5 3v17.5M16 18l2.5 2.5L21 18M8 13.5V17");
}

</style>
