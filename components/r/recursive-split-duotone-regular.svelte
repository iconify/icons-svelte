<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vdjnqqbyj"/><path class="k9l-nbb9m"/><path class="nexmh4h6s"/><path class="v_k9vhbev"/><path class="nc9cq5jtq"/><path class="qugg1kbje"/><path class="c7dgfu7wx"/><path class="lgyhdeb-s"/><path class="j1kezkxcy"/><path class="ezp0d4btt"/><path class="gnit4mb6c"/><path class="lkpe2ldcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recursive-split-duotone-regular" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.ezp0d4btt) {
  d: path("M2 16h3");
}

:global(.gnit4mb6c) {
  d: path("M7.5 16h3");
}

:global(.j1kezkxcy) {
  d: path("M13.5 10H22");
}

:global(.k9l-nbb9m) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 10h8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lgyhdeb-s) {
  d: path("M2 10h8.5");
}

:global(.lkpe2ldcq) {
  d: path("M13.5 16H22");
}

:global(.nc9cq5jtq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nexmh4h6s) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 10H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qugg1kbje) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 16H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v_k9vhbev) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vdjnqqbyj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
