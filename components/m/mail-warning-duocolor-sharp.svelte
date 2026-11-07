<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qotncwb9x"/><path class="bsyq0zp1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-warning-duocolor-sharp" {...props}></Icon>
<style>
:global(.bsyq0zp1v) {
  d: path("M21 13v6H3V5h8M3 5l6 6h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qotncwb9x) {
  stroke-opacity: 0.4;
  d: path("M18 3v3m0 3h.01");
}

</style>
