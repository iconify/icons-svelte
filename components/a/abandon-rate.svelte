<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy4td8f9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:abandon-rate" {...props}></Icon>
<style>
:global(.qy4td8f9f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h13L11 11.5v9H7v-9ZM9 8h12.5m-3-3l3 3l-3 3");
}

</style>
