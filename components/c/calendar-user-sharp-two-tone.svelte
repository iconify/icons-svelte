<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="szjgtkryd"/><path class="g-l_rjcgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-user-sharp-two-tone" {...props}></Icon>
<style>
:global(.g-l_rjcgb) {
  d: path("M17 11C18.1046 11 19 11.8954 19 13C19 14.1046 18.1046 15 17 15C15.8954 15 15 14.1046 15 13C15 11.8954 15.8954 11 17 11ZM13 22L13 21C13 19.8954 13.8954 19 15 19L19 19C20.1046 19 21 19.8954 21 21L21 22");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.szjgtkryd) {
  stroke-opacity: 0.4;
  d: path("M10 21L3 21L3 5L21 5L21 9M6 11L12 11M8 2L8 8M16 2L16 8");
}

</style>
