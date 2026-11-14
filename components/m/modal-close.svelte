<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkz34zbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:modal-close" {...props}></Icon>
<style>
:global(.zkz34zbhk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.375 3.5h9.25A4.375 4.375 0 0 1 21 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 16.125v-8.25A4.375 4.375 0 0 1 7.375 3.5M15 7l2.5 2.5m0-2.5L15 9.5M6.5 13h11m-11 3.5H13");
}

</style>
