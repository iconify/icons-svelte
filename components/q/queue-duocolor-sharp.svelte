<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sloak6mhm"/><path class="bsige7bzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:queue-duocolor-sharp" {...props}></Icon>
<style>
:global(.bsige7bzw) {
  d: path("M3 3h8v6H3Zm0 12h8v6H3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sloak6mhm) {
  stroke-opacity: 0.4;
  d: path("M18 3v18m-3-3l3 3l3-3");
}

</style>
