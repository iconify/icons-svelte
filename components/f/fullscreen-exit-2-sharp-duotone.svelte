<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kypg14bve"/><path class="o8857ob4w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fullscreen-exit-2-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.kypg14bve) {
  stroke-opacity: 0.4;
  d: path("M22 10L14 10L14 2");
}

:global(.o8857ob4w) {
  d: path("M2 14L10 14L10 22");
}

</style>
