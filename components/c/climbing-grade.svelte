<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x878mbbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:climbing-grade" {...props}></Icon>
<style>
:global(.x878mbbpb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5L9 3.5l4 6.5l2.5-2.5l3.5 5m-16.5 8h10m3 .5v-2m3 2v-4m3 4v-6");
}

</style>
