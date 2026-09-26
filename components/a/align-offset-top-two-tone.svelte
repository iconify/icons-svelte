<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to0c2ub7t"><path class="ly67rybbe"/><path class="bvpe1-nac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-top-two-tone" {...props}></Icon>
<style>
:global(.bvpe1-nac) {
  d: path("M16 20L22 20");
}

:global(.ly67rybbe) {
  stroke-opacity: 0.4;
  d: path("M2 4L14 4M4 12L22 12");
}

:global(.to0c2ub7t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
