<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vdjnqqbyj"/><path class="esbu-c2ne"/><path class="y_t81nb0v"/><path class="c7dgfu7wx"/><path class="oy6o-dbxk"/><path class="o1_lmbxyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:curtain-duotone-regular" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.esbu-c2ne) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4v17h5c1.5 0 2 -1 2 -3V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o1_lmbxyf) {
  d: path("M21 4v17h-5c-1.5 0 -2 -1 -2 -3V4");
}

:global(.oy6o-dbxk) {
  d: path("M3 4v17h5c1.5 0 2 -1 2 -3V4");
}

:global(.vdjnqqbyj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y_t81nb0v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 4v17h-5c-1.5 0 -2 -1 -2 -3V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
