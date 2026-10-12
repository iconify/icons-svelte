<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xahtgmb1b"/><path class="d73ngsbty"/><path class="e139mzr-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bassoon-sharp" {...props}></Icon>
<style>
:global(.d73ngsbty) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.5 13.5h.01M14.5 17h.01");
}

:global(.e139mzr-w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.5H8.159L7 6.25l-.5-1.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xahtgmb1b) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75h5v18.5h-5zm0 3.75h5");
}

</style>
