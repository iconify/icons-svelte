<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="o9uj508bp"/><path class="dulwphh-b"/><path class="go1co5b_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:audio-encoder-outline-regular" {...props}></Icon>
<style>
:global(.dulwphh-b) {
  d: path("m15.5 8 2.5 2.5 -2.5 2.5");
}

:global(.go1co5b_o) {
  d: path("M11 10.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jq9hovbrs) {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o9uj508bp) {
  d: path("M8.5 8 6 10.5 8.5 13");
}

:global(.yomctlb4k) {
  d: path("M7 17v4l4 -4");
}

</style>
