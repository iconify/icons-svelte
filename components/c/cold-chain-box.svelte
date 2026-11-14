<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbwq-rewr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cold-chain-box" {...props}></Icon>
<style>
:global(.vbwq-rewr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 6.5h2.5V18a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V6.5H22M12 9.75v7m3.031-5.25L8.969 15m6.062 0l-6.062-3.5");
}

</style>
