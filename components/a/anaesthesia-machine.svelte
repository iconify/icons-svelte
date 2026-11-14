<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdqv_6b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:anaesthesia-machine" {...props}></Icon>
<style>
:global(.hdqv_6b4q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7za3 3 0 0 1 3 3v8.5a3 3 0 0 1-3 3a3 3 0 0 1-3-3V10a3 3 0 0 1 3-3m0 0V3M5 3h4m0 0c6 0 8 3 8 8.5m-3.5 0h7l-1.25 4c-.5 1.75-4 1.75-4.5 0Z");
}

</style>
