<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl7q_k5wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:nesting-tables" {...props}></Icon>
<style>
:global(.cl7q_k5wt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5h13m-12 0v15m11-15v15M6.5 11h12m-1 0v10.5m-7-6h11m-1 0v6");
}

</style>
