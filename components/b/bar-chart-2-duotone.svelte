<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bx1pax0sa"/><path class="vqkc50bpn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-2-duotone" {...props}></Icon>
<style>
:global(.bx1pax0sa) {
  stroke-opacity: 0.4;
  d: path("M12 9L12 22M20 2L20 22");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vqkc50bpn) {
  d: path("M4 16L4 22");
}

</style>
