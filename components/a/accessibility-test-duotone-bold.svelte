<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_vo3wz-j"/><path class="yeoa2yx7i"/><path class="czoh5nbjc"/><path class="i36zaq-hn"/><path class="fozhwebbv"/><path class="tl_0od7zv"/><path class="ysxlqwpgz"/><path class="aaofdybgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:accessibility-test-duotone-bold" {...props}></Icon>
<style>
:global(.aaofdybgo) {
  d: path("m9 18 3 -3 3 3");
}

:global(.czoh5nbjc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10.5V15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fozhwebbv) {
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.i36zaq-hn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 18 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s_vo3wz-j) {
  fill: currentColor;
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tl_0od7zv) {
  d: path("M6 10.5h12");
}

:global(.yeoa2yx7i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10.5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ysxlqwpgz) {
  d: path("M12 10.5V15");
}

</style>
