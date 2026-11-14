<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpndd-b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fight-shorts" {...props}></Icon>
<style>
:global(.zpndd-b8j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 7.25l-1.5 13h7.5l1.5-7l1.5 7H21l-1.5-13v-3.5h-15Zm0 0h15");
}

</style>
