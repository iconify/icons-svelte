<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bbvxd2mjs"/><path class="pg0en1bcd"/><path class="qoxqdyb0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:label-review-outline-regular" {...props}></Icon>
<style>
:global(.bbvxd2mjs) {
  d: path("M3 6h10l3.5 3.5L13 13H3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pg0en1bcd) {
  d: path("M13 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.qoxqdyb0z) {
  d: path("m18.5 19.5 2 2");
}

</style>
