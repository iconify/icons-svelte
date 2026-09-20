<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oqavd2byi"/><path class="jxd4hqxjs"/><path class="w6_tlja0w"/><path class="wneoubc6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:incremental-model-outline-regular" {...props}></Icon>
<style>
:global(.jxd4hqxjs) {
  d: path("m6 9 6 -6 6 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqavd2byi) {
  d: path("M2 16a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

:global(.w6_tlja0w) {
  d: path("M12 3v10");
}

:global(.wneoubc6n) {
  d: path("M7 21h10");
}

</style>
