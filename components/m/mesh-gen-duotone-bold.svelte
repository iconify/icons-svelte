<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oq71y_3bz"/><path class="h2sq3fbpa"/><path class="sswv2gbcf"/><path class="d-_x6ccub"/><path class="j835zw5-z"/><path class="xyj-l9cjp"/><path class="k7ro6rbzz"/><path class="dgfbh6b4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mesh-gen-duotone-bold" {...props}></Icon>
<style>
:global(.d-_x6ccub) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dgfbh6b4z) {
  d: path("M12 9v9");
}

:global(.h2sq3fbpa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.k7ro6rbzz) {
  d: path("m3 18 9 -9 9 9");
}

:global(.oq71y_3bz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sswv2gbcf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 18 9 -9 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
