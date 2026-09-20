<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="g8np0sarh"/><path class="mk-5e0q8i"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="xyvj9ibgz"/><path class="zpx9azgmt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gradient-duotone-thin" {...props}></Icon>
<style>
:global(.g8np0sarh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 6 5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mk-5e0q8i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 16h4v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.xyvj9ibgz) {
  d: path("m6 6 5 5 5 5");
}

:global(.yu-j7jb_g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zpx9azgmt) {
  d: path("M12 16h4v-4");
}

</style>
