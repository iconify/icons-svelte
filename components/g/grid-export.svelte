<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uucm2pbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:grid-export" {...props}></Icon>
<style>
:global(.uucm2pbyk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21.5L8.5 3L13 21.5M3 7.5h11m-9 5h7m3-.5h6m-2.5-2.5L21 12l-2.5 2.5");
}

</style>
