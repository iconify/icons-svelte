<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5v54kp1e"/><path class="lhbszdb8j"/><path class="km5lv4b7f"/><path class="ri2m-q_tv"/><path class="wwogglmvt"/><path class="lpz1dcbuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rollback-auto-duotone-regular" {...props}></Icon>
<style>
:global(.km5lv4b7f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11.5 9.5 9 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lhbszdb8j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lpz1dcbuc) {
  d: path("M11.5 9.5 9 12l2.5 2.5");
}

:global(.n5v54kp1e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ri2m-q_tv) {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

:global(.wwogglmvt) {
  d: path("M9 12h8");
}

</style>
