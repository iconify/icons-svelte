<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdk-ougga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:face-mask-cloth" {...props}></Icon>
<style>
:global(.kdk-ougga) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8C9 6.5 15 6.5 18.5 8v6.5c-3.5 3-9.5 3-13 0Zm0 1c-2.75 0-2.75 4.5 0 4.5m13-4.5c2.75 0 2.75 4.5 0 4.5m-10-3h7m-6 2.75h5");
}

</style>
