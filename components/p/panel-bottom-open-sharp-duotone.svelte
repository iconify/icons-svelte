<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hifn7hyur"/><path class="f4kpv4bkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-bottom-open-sharp-duotone" {...props}></Icon>
<style>
:global(.f4kpv4bkd) {
  d: path("M8.7071 11.2929L12 8L15.2929 11.2929");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.hifn7hyur) {
  stroke-opacity: 0.4;
  d: path("M3 3L21 3L21 21L3 21L3 3ZM3 15L21 15");
}

</style>
