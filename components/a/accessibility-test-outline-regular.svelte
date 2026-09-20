<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fozhwebbv"/><path class="tl_0od7zv"/><path class="ysxlqwpgz"/><path class="aaofdybgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:accessibility-test-outline-regular" {...props}></Icon>
<style>
:global(.aaofdybgo) {
  d: path("m9 18 3 -3 3 3");
}

:global(.fozhwebbv) {
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tl_0od7zv) {
  d: path("M6 10.5h12");
}

:global(.ysxlqwpgz) {
  d: path("M12 10.5V15");
}

</style>
