<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpa_o4kef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pollen-grass" {...props}></Icon>
<style>
:global(.bpa_o4kef) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21h18M8 21q-1-5-3.5-9m7.5 9V10m4 11q1-5 3.5-9M6 8h.01M12 5.5h.01M18 8h.01");
}

</style>
