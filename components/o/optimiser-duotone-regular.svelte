<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="go3vib-_k"/><path class="l3z1h6r5i"/><path class="festcnvxk"/><path class="bx3fv3b8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:optimiser-duotone-regular" {...props}></Icon>
<style>
:global(.bx3fv3b8c) {
  d: path("M12 13v4");
}

:global(.festcnvxk) {
  d: path("m3 7 6 6h6l6 -6");
}

:global(.go3vib-_k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 7 6 6h6l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l3z1h6r5i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
