<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="h3qfj6bgc"/><path class="z2xx1pboh"/><path class="kvzrrkb_u"/><path class="r3faxubne"/><path class="be1u5t58a"/><path class="h50arts9k"/><path class="ojg4edcfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-episodic-duotone-thin" {...props}></Icon>
<style>
:global(.be1u5t58a) {
  d: path("M6 8h14");
}

:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h3qfj6bgc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h50arts9k) {
  d: path("M6 12h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kvzrrkb_u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ojg4edcfp) {
  d: path("M6 16h14");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.z2xx1pboh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
