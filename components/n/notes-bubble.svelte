<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl_oygboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:notes-bubble" {...props}></Icon>
<style>
:global(.hl_oygboe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h12a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-8l-4 4v-4a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3m1 5h10M7 13h10");
}

</style>
