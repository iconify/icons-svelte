<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qy-vhrjxc"/><path class="tv3a5iipi"/><path class="r1gclvbbm"/><path class="ks2swpbkw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:done-all-duotone-regular" {...props}></Icon>
<style>
:global(.ks2swpbkw) {
  d: path("m9 12 5 5 8 -8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qy-vhrjxc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 12 5 5 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r1gclvbbm) {
  d: path("m2 12 5 5 8 -8");
}

:global(.tv3a5iipi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 12 5 5 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
