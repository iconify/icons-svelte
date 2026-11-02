<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fxfr12bzu"/><path class="ht3krccrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:droplet-duocolor-sharp" {...props}></Icon>
<style>
:global(.fxfr12bzu) {
  stroke-opacity: 0.4;
  d: path("M15 14a3 3 0 0 1-3 3");
}

:global(.ht3krccrn) {
  d: path("M12 3S5 8 5 14a7 7 0 0 0 14 0c0-6-7-11-7-11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
