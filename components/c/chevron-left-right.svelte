<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t12c18b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chevron-left-right" {...props}></Icon>
<style>
:global(.t12c18b3l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 7.5L19 12l-4.5 4.5m-5-9L5 12l4.5 4.5");
}

</style>
