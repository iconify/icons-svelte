<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfaip27ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cast-connected" {...props}></Icon>
<style>
:global(.nfaip27ho) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8V6.5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v5.75M3 16a3.5 3.5 0 0 1 3.5 3.5M3 12a7.5 7.5 0 0 1 7.5 7.5m4.25-1.5l2 2L21 15.75");
}

</style>
