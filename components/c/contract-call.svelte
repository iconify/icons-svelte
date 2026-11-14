<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikriqb9kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:contract-call" {...props}></Icon>
<style>
:global(.ikriqb9kl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 6l-4 6l4 6m3-12l4 6l-4 6m11.5-6H17m2.5-2.5L17 12l2.5 2.5");
}

</style>
