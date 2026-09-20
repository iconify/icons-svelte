<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="icdzo3brn"/><path class="xdkaxb-wa"/><path class="y_alpccpl"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="pty_wsbvs"/><path class="s2pzwwb8y"/><path class="s4_6dccau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coverage-gap-duotone-regular" {...props}></Icon>
<style>
:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.icdzo3brn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ku_telleq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

:global(.s2pzwwb8y) {
  d: path("m10.5 12.5 3 3");
}

:global(.s4_6dccau) {
  d: path("m13.5 12.5 -3 3");
}

:global(.wywiukbgn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xdkaxb-wa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10.5 12.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y_alpccpl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13.5 12.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
