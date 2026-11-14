<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b167bo_cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:face-buttons" {...props}></Icon>
<style>
:global(.b167bo_cs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m0 13a3 3 0 1 0 6 0a3 3 0 1 0-6 0M2.5 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0m13 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
