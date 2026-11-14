<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgu8q6bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:drug-test" {...props}></Icon>
<style>
:global(.rgu8q6bpy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3h6m-5 0v4m4-4v4m-4 0v10a2 2 0 0 0 4 0V7m-4 5h4");
}

</style>
