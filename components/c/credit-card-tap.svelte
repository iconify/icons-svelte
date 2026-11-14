<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f1lcbmbja"/><path class="vrr0vxb2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:credit-card-tap" {...props}></Icon>
<style>
:global(.f1lcbmbja) {
  d: path("M2.5 4.25h19v15.5h-19Zm5 7.75h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vrr0vxb2o) {
  d: path("M9.99 9.911a3.25 3.25 0 0 1 0 4.178m2.834-5.817a6.5 6.5 0 0 1 0 7.456m3.12-8.603a9.75 9.75 0 0 1 0 9.75");
}

</style>
