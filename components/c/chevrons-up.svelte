<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv_l6hb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chevrons-up" {...props}></Icon>
<style>
:global(.jv_l6hb-n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11.5L12 6l5.5 5.5m-11 6L12 12l5.5 5.5");
}

</style>
