<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pzck7wbzu"/><path class="zu2u1mcjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:reply-all-two-tone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pzck7wbzu) {
  stroke-opacity: 0.4;
  d: path("M14 4L8 10L14 16M8 10L18 10C20.2091 10 22 11.7909 22 14L22 20");
}

:global(.zu2u1mcjz) {
  d: path("M8 4L2 10L8 16");
}

</style>
