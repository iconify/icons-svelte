<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a24v_9qyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:currency-rand" {...props}></Icon>
<style>
:global(.a24v_9qyu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 19.5v-15h5c2.5 0 4 1.5 4 4s-1.5 4-4 4H8m4.75 0l4.25 7");
}

</style>
