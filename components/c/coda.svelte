<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c58r6nb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coda" {...props}></Icon>
<style>
:global(.c58r6nb9s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12a5 6.5 0 1 0 10 0a5 6.5 0 1 0-10 0m5-9.5v19M2.5 12h19");
}

</style>
