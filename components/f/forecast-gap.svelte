<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjsxlo3-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:forecast-gap" {...props}></Icon>
<style>
:global(.hjsxlo3-z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v17.5H21m-13-3V14m4.5 3.5V11m4.5 6.5v-5m-10.5-6h2m2.75 0h2m2.75 0h2");
}

</style>
