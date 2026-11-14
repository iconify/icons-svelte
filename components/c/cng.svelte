<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmhen5_8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cng" {...props}></Icon>
<style>
:global(.gmhen5_8t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21.5V11a5 5 0 0 1 10 0v10.5ZM12 3v3M9.5 3h5");
}

</style>
