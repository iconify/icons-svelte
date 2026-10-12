<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qnq20nbxf"/><path class="llcwhnlol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:church-bell-sharp" {...props}></Icon>
<style>
:global(.llcwhnlol) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19.5h.01");
}

:global(.qnq20nbxf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h18.5m-17 0v18m15.5-18v18M12 3.25v2.5m0 0c2.75 0 4.25 2.25 4.25 5.25v3.75l1 2H6.75l1-2V11c0-3 1.5-5.25 4.25-5.25Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
