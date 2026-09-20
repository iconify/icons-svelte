<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fh4c1v02p"/><path class="bbye9-bll"/><path class="i5d2grbwo"/><path class="s27ukbqxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corpus-duotone-regular" {...props}></Icon>
<style>
:global(.bbye9-bll) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 8H9v14h10V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fh4c1v02p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 2H6v14h10V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i5d2grbwo) {
  d: path("M13 2H6v14h10V5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s27ukbqxc) {
  d: path("M16 8H9v14h10V11");
}

</style>
