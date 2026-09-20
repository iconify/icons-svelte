<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bpciasb2z"/><path class="c11_n0b6s"/><path class="k3juqlbuw"/><path class="eytzvnbei"/><path class="bzop3hedr"/><path class="qhdfwccdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkout-step-outline-regular" {...props}></Icon>
<style>
:global(.bpciasb2z) {
  d: path("M3 5.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.bzop3hedr) {
  d: path("M10.5 10.5h3");
}

:global(.c11_n0b6s) {
  d: path("M6.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.eytzvnbei) {
  d: path("M6.5 10.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.k3juqlbuw) {
  d: path("M15.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qhdfwccdf) {
  d: path("M13.5 10.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
