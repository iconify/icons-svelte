<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a9ai-ogdl"/><path class="je03xdcdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:audio-lines-low-sharp-duotone" {...props}></Icon>
<style>
:global(.a9ai-ogdl) {
  stroke-opacity: 0.4;
  d: path("M8 9V15M16 10V14");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.je03xdcdh) {
  d: path("M4 10V14M12 7V17M20 9V15");
}

</style>
