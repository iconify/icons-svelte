<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4ejqnzqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:power" {...props}></Icon>
<style>
:global(.g4ejqnzqi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 6.072a8 8 0 1 1-8 0M12 3v8");
}

</style>
