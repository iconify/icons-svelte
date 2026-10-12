<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="epe7d9bhf"/><path class="nczoc976s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:camcorder-sharp" {...props}></Icon>
<style>
:global(.epe7d9bhf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75h3.5v7.5h-3.5zm3.5 3.75H8.5m0-4.75h9v10.5h-9zm9 2.25h3.75v6H17.5z");
}

:global(.nczoc976s) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.5 10h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
