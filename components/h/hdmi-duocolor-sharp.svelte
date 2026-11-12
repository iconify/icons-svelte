<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zzutjwbbr"/><path class="ctzd7e6ig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hdmi-duocolor-sharp" {...props}></Icon>
<style>
:global(.ctzd7e6ig) {
  d: path("M3 7h18v4l-4 6H7l-4-6z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zzutjwbbr) {
  stroke-opacity: 0.4;
  d: path("M8 11h8");
}

</style>
