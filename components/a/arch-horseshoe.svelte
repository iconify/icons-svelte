<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8g9jfhrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arch-horseshoe" {...props}></Icon>
<style>
:global(.n8g9jfhrp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5V11a8.5 8.5 0 0 1 17 0v10.5H15v-7a5 5 0 1 0-6 0v7Zm0-7H9m6 0h5.5");
}

</style>
