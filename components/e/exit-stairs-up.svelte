<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="paq6ojbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:exit-stairs-up" {...props}></Icon>
<style>
:global(.paq6ojbht) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21h5v-4h5v-4h5V9h4M9 13V3M6 5.75l3-3l3 3");
}

</style>
