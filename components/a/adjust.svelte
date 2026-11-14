<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0l7gsbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:adjust" {...props}></Icon>
<style>
:global(.s0l7gsbsf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h3m7 0h9m-16 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
