<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="korpvc72p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bone-folder" {...props}></Icon>
<style>
:global(.korpvc72p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.5Q13 14.5 20 6a1.5 1.5 0 0 0-2-2Q9.5 11 2.5 18.5Zm0-3L9 15");
}

</style>
