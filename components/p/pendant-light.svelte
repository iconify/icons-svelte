<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y56-uubby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pendant-light" {...props}></Icon>
<style>
:global(.y56-uubby) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V7m-7 6a7 6 0 0 1 14 0Zm7 3v5m-5-5.25L4.5 20M17 15.75L19.5 20");
}

</style>
