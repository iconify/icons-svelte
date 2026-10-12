<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwydwtbga"/><path class="dnormzgzu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:like-burst" {...props}></Icon>
<style>
:global(.dnormzgzu) {
  d: path("M9.75 16.5v-5l1.85-3.3a1.05 1.05 0 0 1 1.95.75l-.45 1.8h2.45a1.15 1.15 0 0 1 1.1 1.4l-.75 3.05a1.15 1.15 0 0 1-1.1.85ZM7.5 11.75v4.5");
}

:global(.gwydwtbga) {
  d: path("M8.3 19.43a8.75 8.75 0 1 0-4.23-4.23l-.67 4.35c-.1.6.45 1.1 1 .95Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
