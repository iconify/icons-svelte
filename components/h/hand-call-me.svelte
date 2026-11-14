<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqhdvi0rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hand-call-me" {...props}></Icon>
<style>
:global(.gqhdvi0rk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21.5v-4l-5-5a1.75 1.75 0 0 1 2.25-2.25L9 13v-2a1 1 0 0 1 1-1h5l3-5.5a1.5 1.5 0 0 1 2.5 1.25l-3 6.25v5.5l-1 4m-5-8H15");
}

</style>
