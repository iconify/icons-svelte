<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bkiaatbvd"/><path class="n75imzbwr"/><path class="jkuojibnm"/><path class="bih55pzif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:beekeeping-outline-regular" {...props}></Icon>
<style>
:global(.bih55pzif) {
  d: path("M11 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.bkiaatbvd) {
  d: path("M5 5h14v4H5Z");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.n75imzbwr) {
  d: path("M5 12h14v4H5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
