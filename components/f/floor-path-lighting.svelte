<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5jz5vnlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:floor-path-lighting" {...props}></Icon>
<style>
:global(.e5jz5vnlk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V3.5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1V21m-2.75-9h.01M3 21h.01M6 21h.01M9 21h.01");
}

</style>
