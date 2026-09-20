<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vyks9vbfn"/><path class="mpjdm200q"/><path class="tkeq0bpvv"/><path class="gcnz6cc5q"/><path class="artopbq8l"/><path class="ephqv81ta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:map-fold-outline-regular" {...props}></Icon>
<style>
:global(.artopbq8l) {
  d: path("M12 7.5v9");
}

:global(.ephqv81ta) {
  d: path("m9.5 14 2.5 2.5 2.5 -2.5");
}

:global(.gcnz6cc5q) {
  d: path("M9.5 10 12 7.5l2.5 2.5");
}

:global(.mpjdm200q) {
  d: path("M6 4v16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tkeq0bpvv) {
  d: path("M18 4v16");
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
