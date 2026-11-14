<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cux71ld7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:maintainer" {...props}></Icon>
<style>
:global(.cux71ld7c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.272 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.437 0 2.76.257 3.882.724M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m13 7.25a2.5 2.5 0 1 0 2.25 2.25m-4.25 2L15 21");
}

</style>
