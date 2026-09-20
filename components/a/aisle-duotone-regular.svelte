<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e06o29xir"/><path class="am603abae"/><path class="td6ul9qiy"/><path class="eer1psboe"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="qxpc-f42y"/><path class="f5e6x3ddq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:aisle-duotone-regular" {...props}></Icon>
<style>
:global(.am603abae) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e06o29xir) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eer1psboe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f5e6x3ddq) {
  d: path("M14.5 12v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qxpc-f42y) {
  d: path("M9.5 12v7");
}

:global(.td6ul9qiy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tp7101bon) {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

:global(.yb0d-pkkp) {
  d: path("M4 8v14h16V8");
}

</style>
