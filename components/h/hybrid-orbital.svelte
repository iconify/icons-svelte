<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzglxusue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hybrid-orbital" {...props}></Icon>
<style>
:global(.wzglxusue) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 12l-2-6.25a2.25 2.25 0 1 1 4 0Zm0 0l2 5.25a2.25 2.25 0 1 1-4 0Zm0 0h6.25A2.25 2.25 0 1 1 17 16Zm0 0l-5 4a2.25 2.25 0 1 1-1.25-4Z");
}

</style>
