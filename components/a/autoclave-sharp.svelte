<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jxg23w0rw"/><path class="vzimnlbjx"/><circle class="x6r1rg4bu"/><path class="byty_cczq"/><path class="axvnh-z7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:autoclave-sharp" {...props}></Icon>
<style>
:global(.axvnh-z7j) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 10h2m-2 2.75h2M6 19.5v1.75m12-1.75v1.75");
}

:global(.byty_cczq) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 6.5h.01");
}

:global(.jxg23w0rw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h18.5V19.5H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vzimnlbjx) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6a5.5 5.5 0 1 1 0 11a5.5 5.5 0 1 1 0-11Zm0 0v2.5m0 6V17M5 11.5h2.5m6 0H16");
}

:global(.x6r1rg4bu) {
  cx: 10.5px;
  cy: 11.5px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
