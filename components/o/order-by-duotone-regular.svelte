<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="cozt1f-wy"/><path class="n9xsuobeo"/><path class="e79pod60b"/><path class="k6nj2fbya"/><path class="qxnpdo0dk"/><path class="zuu1wnb1v"/><path class="o46_3ibvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:order-by-duotone-regular" {...props}></Icon>
<style>
:global(.cozt1f-wy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 10h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e79pod60b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.mkh6f026t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n9xsuobeo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 15h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o46_3ibvz) {
  d: path("M3 20h6");
}

:global(.qxnpdo0dk) {
  d: path("M3 10h14");
}

:global(.zuu1wnb1v) {
  d: path("M3 15h10");
}

</style>
