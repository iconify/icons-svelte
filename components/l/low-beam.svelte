<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-czjnbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:low-beam" {...props}></Icon>
<style>
:global(.y-czjnbbb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 6c4.25 0 7 2.5 7 6s-2.75 6-7 6Zm-10 1.5l6 2m-6 2.5l6 2m-6 2.5l6 2");
}

</style>
