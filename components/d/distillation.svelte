<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhh4_c83z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:distillation" {...props}></Icon>
<style>
:global(.zhh4_c83z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4v5.75a5.5 5.5 0 1 0 3 0V4m0 1.5L20 11m-1 3s-2.75 3-2.75 5a2.75 2.75 0 0 0 5.5 0c0-2-2.75-5-2.75-5");
}

</style>
