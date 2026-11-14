<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_k5n4bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cause-equality" {...props}></Icon>
<style>
:global(.y_k5n4bue) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.5h13a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2a2 2 0 0 1 2-2m0 7h13a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2a2 2 0 0 1 2-2");
}

</style>
