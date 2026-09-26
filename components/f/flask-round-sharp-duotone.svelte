<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oana6q3yt"/><path class="jwbs-piju"/><path class="dx93_50hj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flask-round-sharp-duotone" {...props}></Icon>
<style>
:global(.dx93_50hj) {
  d: path("M7 2L17 2");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.jwbs-piju) {
  fill: currentColor;
  d: path("M4 15L20 15C20 19.4183 16.4183 23 12 23C7.5817 23 4 19.4183 4 15Z");
  stroke: none;
}

:global(.oana6q3yt) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.5 1L14.5 1C15.0523 1 15.5 1.4477 15.5 2L15.5 7.8063C18.2529 9.1456 20 11.9386 20 15C20 19.4183 16.4183 23 12 23C7.5817 23 4 19.4183 4 15C4 11.9386 5.7471 9.1456 8.5 7.8063L8.5 2C8.5 1.4477 8.9477 1 9.5 1Z");
  stroke: none;
}

</style>
