<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to0c2ub7t"><path class="e8lb8uc3g"/><path class="l12_cmb5r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-bottom-duotone" {...props}></Icon>
<style>
:global(.e8lb8uc3g) {
  stroke-opacity: 0.4;
  d: path("M4 12L22 12M2 20L14 20");
}

:global(.l12_cmb5r) {
  d: path("M16 4L22 4");
}

:global(.to0c2ub7t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
