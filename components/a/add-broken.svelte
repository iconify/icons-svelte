<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z5l_mobdk"/><path class="g121b32ky"/><path class="etg41e6bw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:add-broken" {...props}></Icon>
<style>
:global(.etg41e6bw) {
  d: path("M12.0204 4L12.0205 20.0003");
}

:global(.g121b32ky) {
  d: path("M16 12L20 12");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z5l_mobdk) {
  d: path("M4 12L12 12");
}

</style>
