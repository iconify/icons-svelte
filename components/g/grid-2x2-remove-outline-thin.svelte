<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mu0i9zbhe"/><path class="x26a8iq1c"/><path class="x64w0obso"/><path class="m26ojxb3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:grid-2x2-remove-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m26ojxb3w) {
  d: path("M14 17h6");
}

:global(.mu0i9zbhe) {
  d: path("M14 2h5a3 3 0 0 1 3 3v14a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3h5");
}

:global(.x26a8iq1c) {
  d: path("M2 12h20");
}

:global(.x64w0obso) {
  d: path("M12 2v20");
}

</style>
