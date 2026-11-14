<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og37t3zye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-fire-hydrant" {...props}></Icon>
<style>
:global(.og37t3zye) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8c0-3 2-5 4.5-5s4.5 2 4.5 5m-11 0h13m-11 0v13m9-13v13M5 21h14M7.5 11.5h-3v4h3m9-4h3v4h-3");
}

</style>
