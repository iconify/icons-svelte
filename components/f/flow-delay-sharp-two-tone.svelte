<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o-lbwj97j"/><path class="qged_tb8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flow-delay-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o-lbwj97j) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 12L1 5C1 4.4477 1.4477 4 2 4L15 4C19.4183 4 23 7.5817 23 12C23 16.4183 19.4183 20 15 20L2 20C1.4477 20 1 19.5523 1 19Z");
  stroke: none;
}

:global(.qged_tb8d) {
  d: path("M2 5L15 5C18.866 5 22 8.134 22 12C22 15.866 18.866 19 15 19L2 19Z");
}

</style>
