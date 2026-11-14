<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quh8nn-yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hi-vis-vest" {...props}></Icon>
<style>
:global(.quh8nn-yi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5L9 8v12.5h6V8l2-4.5L21 6v6h-4v8.5H7V12H3V6Z");
}

</style>
