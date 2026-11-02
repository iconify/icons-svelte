<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mh_q-d6ev"/><path class="c_2oglksg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-2-duocolor-sharp" {...props}></Icon>
<style>
:global(.c_2oglksg) {
  d: path("M3 20h18m-9 0V4H5v16");
}

:global(.mh_q-d6ev) {
  stroke-opacity: 0.4;
  d: path("m12 11l2-2l5 5v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
