<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwubodd9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:longliner" {...props}></Icon>
<style>
:global(.jwubodd9p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h19L19 13H5Zm3 0V4h5v4m8.5 5v6a2 2 0 0 1-4 0v-1.5");
}

</style>
