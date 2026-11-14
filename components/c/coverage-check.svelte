<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr9a6qoku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coverage-check" {...props}></Icon>
<style>
:global(.yr9a6qoku) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21v-5m4.5 5V10M12 21v-2.9m0-.2V3.5M14.75 18l2 2L21 15.75");
}

</style>
