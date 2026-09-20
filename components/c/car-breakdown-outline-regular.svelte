<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sqwju3bsh"/><path class="du3agkbjb"/><path class="fquh7rbnp"/><path class="jqdaf4bpj"/><path class="vqi6vft7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:car-breakdown-outline-regular" {...props}></Icon>
<style>
:global(.du3agkbjb) {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fquh7rbnp) {
  d: path("M15 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.jqdaf4bpj) {
  d: path("M12 9.5v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sqwju3bsh) {
  d: path("M2 16V8.5h4L9.5 5h5L18 8.5h4V16Z");
}

:global(.vqi6vft7m) {
  d: path("M11 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
