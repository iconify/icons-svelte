<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ss0oax1ix"/><path class="fypycbc0s"/><path class="isxmsmb2n"/><path class="sjh-zdctz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:loot-box-sharp" {...props}></Icon>
<style>
:global(.fypycbc0s) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 14.5a1.5 1.5 0 1 1 2.1 1.37l-.6.27V17");
}

:global(.isxmsmb2n) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19h.01");
}

:global(.sjh-zdctz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V5M6.75 3.5l1 1.75m9.5-1.75l-1 1.75");
}

:global(.ss0oax1ix) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75h18.5v3H2.75zm1.25 3h16v10.5H4z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
