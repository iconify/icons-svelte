<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nmmk5p_xc"/><path class="akhe8vn1q"/><path class="v5bcfeb_i"/><path class="hjzvc-b8b"/><path class="qxn8isffb"/><path class="lbkuffism"/><path class="tj_906bjf"/><path class="l8dn9jbyp"/><path class="w60p31c9m"/><path class="e2nq-yvbg"/><path class="e-3fufbxq"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-balcony-duotone-regular" {...props}></Icon>
<style>
:global(.akhe8vn1q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e-3fufbxq) {
  d: path("M19 15v6");
}

:global(.e2nq-yvbg) {
  d: path("M12 15v6");
}

:global(.hjzvc-b8b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.lbkuffism) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nmmk5p_xc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v9h16V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.qxn8isffb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tj_906bjf) {
  d: path("M4 3v9h16V3");
}

:global(.v5bcfeb_i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w60p31c9m) {
  d: path("M5 15v6");
}

</style>
