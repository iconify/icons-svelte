<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uw5kuce7r"/><path class="sowhn7f6a"/><path class="v0nv9evjn"/><path class="m02rt1bwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:motorsport-outline-regular" {...props}></Icon>
<style>
:global(.m02rt1bwx) {
  d: path("M13 14V9h7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sowhn7f6a) {
  d: path("M6 4h14v10H6Z");
}

:global(.uw5kuce7r) {
  d: path("M3 3v18");
}

:global(.v0nv9evjn) {
  d: path("M6 9h7V4");
}

</style>
