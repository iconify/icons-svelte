<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j-8wz9b1s"/><path class="ml9xssolm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-down-two-tone" {...props}></Icon>
<style>
:global(.j-8wz9b1s) {
  stroke-opacity: 0.4;
  d: path("M4 2L4 15M12 2L12 22");
}

:global(.ml9xssolm) {
  d: path("M20 2L20 8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
