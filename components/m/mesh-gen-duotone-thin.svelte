<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="epwe3rblo"/><path class="hf_gtezns"/><path class="ilenwpbkm"/><path class="h-8pk037m"/><path class="j835zw5-z"/><path class="xyj-l9cjp"/><path class="k7ro6rbzz"/><path class="dgfbh6b4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mesh-gen-duotone-thin" {...props}></Icon>
<style>
:global(.dgfbh6b4z) {
  d: path("M12 9v9");
}

:global(.epwe3rblo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h-8pk037m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hf_gtezns) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ilenwpbkm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 18 9 -9 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.k7ro6rbzz) {
  d: path("m3 18 9 -9 9 9");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
