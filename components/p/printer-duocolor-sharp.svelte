<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uit7r8ros"/><path class="hhtt84bzu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:printer-duocolor-sharp" {...props}></Icon>
<style>
:global(.hhtt84bzu) {
  d: path("M6 17H3V7h18v10h-3M6 7V3h12v4m-8 4h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uit7r8ros) {
  stroke-opacity: 0.4;
  d: path("M6 15h12v6H6Z");
}

</style>
