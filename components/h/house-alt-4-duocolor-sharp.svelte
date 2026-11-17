<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zuh2np-5q"/><path class="l92hkn1dp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-4-duocolor-sharp" {...props}></Icon>
<style>
:global(.l92hkn1dp) {
  d: path("m3 11l9-8l9 8m-2-1.778V21H5V9.222");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zuh2np-5q) {
  stroke-opacity: 0.4;
  d: path("m12 9l3 2.667V17H9v-5.333z");
}

</style>
