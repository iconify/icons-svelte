<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xu26xtb0r"/><path class="kvrmbhbmk"/><path class="e_cac_uni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cookie-jar-sharp" {...props}></Icon>
<style>
:global(.e_cac_uni) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 12.75h.01M12.5 16h.01");
}

:global(.kvrmbhbmk) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.59 12.52a4.75 4.75 0 1 1-2.21-2.88a1.9 1.9 0 0 0 2.21 2.88Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xu26xtb0r) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v3.5H2.75zm1 3.5h16.5v15H3.75z");
}

</style>
