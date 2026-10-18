<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwtu_hbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bracket-right-two-tone" {...props}></Icon>
<style>
:global(.vwtu_hbmr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 2L12 2C13.1046 2 14 2.8954 14 4L14 20C14 21.1046 13.1046 22 12 22L10 22");
}

</style>
