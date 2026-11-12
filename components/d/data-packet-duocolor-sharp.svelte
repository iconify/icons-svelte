<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m28wfubmv"/><path class="t9ehae-0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:data-packet-duocolor-sharp" {...props}></Icon>
<style>
:global(.m28wfubmv) {
  stroke-opacity: 0.4;
  d: path("M13 13v3m4-3v3M3 8h2m-2 4h2m-2 4h2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t9ehae-0f) {
  d: path("M9 5h12v14H9Zm0 4h12");
}

</style>
