<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sk-esxbfq"/><path class="s085ieb8x"/><path class="h88mmbbly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coat-sharp" {...props}></Icon>
<style>
:global(.h88mmbbly) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14h.01M12 17.5h.01");
}

:global(.s085ieb8x) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.75 3.25l3.25 7.5l3.25-7.5");
}

:global(.sk-esxbfq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h5.5l1.3.74l.9.52l1.3.74l.07 1.5l.61 13.5l.07 1.5H4.25l.07-1.5l.61-13.5l.07-1.5l1.3-.74l.9-.52l1.3-.74z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
