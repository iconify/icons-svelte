<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="toeeos4em"/><path class="b69m9zacd"/><path class="wxw3awbew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:handheld-console-sharp" {...props}></Icon>
<style>
:global(.b69m9zacd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 5.25h9v6.25h-9zm.25 10.5h3m-1.5-1.5v3");
}

:global(.toeeos4em) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.75h12v18.5H5V2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wxw3awbew) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 16.75h.01m2.24-2h.01");
}

</style>
