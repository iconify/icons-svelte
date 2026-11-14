<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md3n9o_oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blocked-circle" {...props}></Icon>
<style>
:global(.md3n9o_oy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m2.75-6.75l13.5 13.5");
}

</style>
