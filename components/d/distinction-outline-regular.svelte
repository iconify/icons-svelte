<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ztq2uyxtt"/><path class="cgx6h63ll"/><path class="tyca9wtqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:distinction-outline-regular" {...props}></Icon>
<style>
:global(.cgx6h63ll) {
  d: path("M8 13v8l3 -3 3 3v-8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tyca9wtqq) {
  d: path("m9 8 2 2 4 -4");
}

:global(.ztq2uyxtt) {
  d: path("M6 8a6 6 0 1 0 12 0A6 6 0 1 0 6 8");
}

</style>
