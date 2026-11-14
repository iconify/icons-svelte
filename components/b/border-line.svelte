<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4kl5ebvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:border-line" {...props}></Icon>
<style>
:global(.u4kl5ebvy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21l3-3m2-2l3-3m2-2l3-3m2-2l3-3");
}

</style>
