<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohuh5p9_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:exothermic" {...props}></Icon>
<style>
:global(.ohuh5p9_t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 9v2.75a5 5 0 1 0 3 0V9M8 6.25q-1-1 0-2T8 2.5m4 3.75q-1-1 0-2t0-1.75m4 3.75q-1-1 0-2t0-1.75");
}

</style>
