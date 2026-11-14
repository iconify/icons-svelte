<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l26-6vbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:anklet" {...props}></Icon>
<style>
:global(.l26-6vbjr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5a9 5.5 0 1 0 18 0a9 5.5 0 1 0-18 0m9 5.5v1.75m-3 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 0h.01");
}

</style>
