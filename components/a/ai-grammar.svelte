<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceo9a9-ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ai-grammar" {...props}></Icon>
<style>
:global(.ceo9a9-ms) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4h17m-17 6H11m-7.5 6H11m3-6.5l2 2L20 7m-2 7.5q.75 2.75 3.5 3.5q-2.75.75-3.5 3.5q-.75-2.75-3.5-3.5q2.75-.75 3.5-3.5");
}

</style>
