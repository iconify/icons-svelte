<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dx4yo_bup"/><path class="ex75cacie"/><path class="gr0xwwbmg"/><path class="shn2dkcie"/><path class="j835zw5-z"/><path class="xyj-l9cjp"/><path class="k7ro6rbzz"/><path class="dgfbh6b4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mesh-gen-duotone-regular" {...props}></Icon>
<style>
:global(.dgfbh6b4z) {
  d: path("M12 9v9");
}

:global(.dx4yo_bup) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ex75cacie) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gr0xwwbmg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 18 9 -9 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.k7ro6rbzz) {
  d: path("m3 18 9 -9 9 9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.shn2dkcie) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
