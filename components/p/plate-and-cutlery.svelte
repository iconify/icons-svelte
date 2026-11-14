<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezcp1tdpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:plate-and-cutlery" {...props}></Icon>
<style>
:global(.ezcp1tdpv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m-3-8v16m17-16v16");
}

</style>
