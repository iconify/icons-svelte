<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s_vo3wz-j"/><path class="ailv3bq7y"/><path class="e63_lkb9t"/><path class="qqx18ub6l"/><path class="fozhwebbv"/><path class="tl_0od7zv"/><path class="ysxlqwpgz"/><path class="aaofdybgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:accessibility-test-duotone-regular" {...props}></Icon>
<style>
:global(.aaofdybgo) {
  d: path("m9 18 3 -3 3 3");
}

:global(.ailv3bq7y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10.5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e63_lkb9t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 10.5V15");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.qqx18ub6l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 18 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s_vo3wz-j) {
  fill: currentColor;
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tl_0od7zv) {
  d: path("M6 10.5h12");
}

:global(.ysxlqwpgz) {
  d: path("M12 10.5V15");
}

</style>
