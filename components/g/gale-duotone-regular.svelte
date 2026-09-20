<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kl9kvrl9q"/><path class="digwvcbca"/><path class="tvol5dbhf"/><path class="a3tn0ccwp"/><path class="puf3d7viv"/><path class="c5ipzfbmx"/><path class="d8abqfbpc"/><path class="fu2iodbya"/><path class="r_-onzaex"/><path class="gv9l4p83m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gale-duotone-regular" {...props}></Icon>
<style>
:global(.a3tn0ccwp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 19 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c5ipzfbmx) {
  d: path("M3 6h16");
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.digwvcbca) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fu2iodbya) {
  d: path("M3 16h16");
}

:global(.gv9l4p83m) {
  d: path("m21 19 -3 3");
}

:global(.kl9kvrl9q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.puf3d7viv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 19 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r_-onzaex) {
  d: path("m16 19 -3 3");
}

:global(.tvol5dbhf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
