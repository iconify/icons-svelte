<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-_av1b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bold" {...props}></Icon>
<style>
:global(.g-_av1b3g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3.75h6.5a4 4 0 0 1 0 8h-6.5Zm0 8h7.5a4.25 4.25 0 0 1 0 8.5h-7.5Z");
}

</style>
