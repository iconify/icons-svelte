<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0e7h3bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fly-screen" {...props}></Icon>
<style>
:global(.l0e7h3bvp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3h9A3.5 3.5 0 0 1 20 6.5v8a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 14.5v-8A3.5 3.5 0 0 1 7.5 3m-5 18h19M9.25 3v15m5.5-15v15M4 8h16M4 13h16");
}

</style>
