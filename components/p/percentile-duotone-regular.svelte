<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sxvvyfhya"/><path class="cbel1obav"/><path class="h83bd8wcq"/><path class="x6dxy7f3v"/><path class="npavklbqk"/><path class="vdjnqqbyj"/><path class="f1psbbcsw"/><path class="kdl_ri28b"/><path class="lkivjibuo"/><path class="yzvng5w1c"/><path class="e-0451fwt"/><path class="c7dgfu7wx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:percentile-duotone-regular" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.cbel1obav) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e-0451fwt) {
  d: path("M20 16v4");
}

:global(.f1psbbcsw) {
  d: path("M4 15v5");
}

:global(.h83bd8wcq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kdl_ri28b) {
  d: path("M8 11v9");
}

:global(.lkivjibuo) {
  d: path("M12 13v7");
}

:global(.npavklbqk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 16v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sxvvyfhya) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 15v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vdjnqqbyj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x6dxy7f3v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yzvng5w1c) {
  d: path("M16 7v13");
}

</style>
