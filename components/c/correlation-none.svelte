<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2v0oyb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:correlation-none" {...props}></Icon>
<style>
:global(.s2v0oyb7r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5v17h17M7 16h.01M10 7.5h.01M12.5 13h.01M15 8.5h.01m2.99 7h.01");
}

</style>
