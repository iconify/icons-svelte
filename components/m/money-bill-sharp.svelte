<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="p985vxbzq"/><path class="ykqxd291e"/><path class="n19jjrbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:money-bill-sharp" {...props}></Icon>
<style>
:global(.n19jjrbhf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 12h.01m10.99 0h.01");
}

:global(.p985vxbzq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.25h18.5v13.5H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.ykqxd291e) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.81 10.19l-.457-1.16H10.17v1.42c0 1.88 3.8 1.06 3.8 3.07v1.45h-3.389l-.571-1.16M12 7.88v1.16m0 5.93v1.16");
}

</style>
