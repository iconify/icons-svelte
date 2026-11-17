<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bv8jz9bfg"/><path class="s-9jkyo3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-geothermal-duocolor-sharp" {...props}></Icon>
<style>
:global(.bv8jz9bfg) {
  stroke-opacity: 0.4;
  d: path("M12 15v4m-6 2v-2h12v2m-8-2v2m4-2v2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s-9jkyo3v) {
  d: path("m12 3l5.333 4.667V15H6.667V7.667z");
}

</style>
