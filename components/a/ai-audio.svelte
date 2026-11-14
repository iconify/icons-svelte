<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2wqhcbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ai-audio" {...props}></Icon>
<style>
:global(.e2wqhcbfl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10v4m4-8v12m4-15v18m4-14v6m4-3.5v3m-1 3q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3");
}

</style>
