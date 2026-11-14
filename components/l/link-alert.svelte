<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6w5gjw8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:link-alert" {...props}></Icon>
<style>
:global(.m6w5gjw8k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.5H7.5a4.5 4.5 0 0 0 0 9H9m6-9h1.5A4.5 4.5 0 0 1 21 10M8.5 10h7m2.5 4.5v3.25m0 3h.01");
}

</style>
