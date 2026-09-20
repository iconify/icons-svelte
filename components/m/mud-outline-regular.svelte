<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u3pvd_qut"/><path class="i6tuq5bxi"/><path class="zfnkrabzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mud-outline-regular" {...props}></Icon>
<style>
:global(.i6tuq5bxi) {
  d: path("M7 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u3pvd_qut) {
  d: path("M2 16a4 4 0 0 1 6 -2 5 5 0 0 1 8 -1 4 4 0 0 1 6 3v4H2Z");
}

:global(.zfnkrabzj) {
  d: path("M14 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
