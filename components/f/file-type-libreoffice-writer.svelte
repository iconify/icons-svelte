<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG5rtOJcHW" x1="4" x2="28" y1="31" y2="1" gradientUnits="userSpaceOnUse"><stop offset="0" class="wf3cnubds"/><stop offset="1" class="xgv542bpt"/></linearGradient></defs><g class="ywbk9fbil"><path fill="url(#SVG5rtOJcHW)" transform="translate(2 2)scale(.875)" class="v6qbtcbjh"/><path class="y7nzi9tng"/><path class="ck4pcsb0s"/><g transform="translate(2 2)scale(.875)" class="y_9pn2b8h"><rect class="m57ozgltc"/><rect class="qz26vjb6x"/><rect class="ayr2rmdhr"/><rect class="j5fh41y3r"/><rect class="p6gcz0_qu"/><rect class="psnbcacpw"/></g><path class="ymy-1denr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-libreoffice-writer" {...props}></Icon>
<style>
:global(.ayr2rmdhr) {
  width: 7px;
  height: 1px;
  x: 8px;
  y: 17px;
  ry: 0.5px;
}

:global(.ck4pcsb0s) {
  fill-opacity: var(--svg-fill-opacity--0-201, 0.201);
  d: path("M19.5 2h1.225l6.65 6.65v1.225z");
}

:global(.j5fh41y3r) {
  width: 16px;
  height: 1px;
  x: 8px;
  y: 20px;
  ry: 0.5px;
}

:global(.m57ozgltc) {
  width: 7px;
  height: 1px;
  x: 8px;
  y: 13px;
  ry: 0.5px;
}

:global(.p6gcz0_qu) {
  width: 16px;
  height: 1px;
  x: 8px;
  y: 22px;
  ry: 0.5px;
}

:global(.psnbcacpw) {
  width: 7px;
  height: 1px;
  x: 8px;
  y: 24px;
  ry: 0.5px;
}

:global(.qz26vjb6x) {
  width: 7px;
  height: 1px;
  x: 8px;
  y: 15px;
  ry: 0.5px;
}

:global(.v6qbtcbjh) {
  d: path("M7 0C4.784 0 3 1.784 3 4v24c0 2.216 1.784 4 4 4h18c2.216 0 4-1.784 4-4V12L17 0zm13 0l9 9V0z");
}

:global(.wf3cnubds) {
  stop-color: var(--svg-color--083fa6, #083fa6);
}

:global(.xgv542bpt) {
  stop-color: var(--svg-color--2dcbfd, #2dcbfd);
}

:global(.y_9pn2b8h) {
  fill: var(--svg-color--fafafa, #fafafa);
}

:global(.y7nzi9tng) {
  fill-opacity: var(--svg-fill-opacity--0-199, 0.199);
  d: path("M4.625 25.625v.875c0 1.939 1.561 3.5 3.5 3.5h15.75c1.939 0 3.5-1.561 3.5-3.5v-.875c0 1.939-1.561 3.5-3.5 3.5H8.125a3.49 3.49 0 0 1-3.5-3.5");
}

:global(.ymy-1denr) {
  fill: var(--svg-color--9ae9f9, #9ae9f9);
  d: path("M17.75 13.375a.873.873 0 0 0-.875.875v2.625c0 .485.39.875.875.875h4.375c.485 0 .875-.39.875-.875V14.25a.873.873 0 0 0-.875-.875zm3.938.875a.44.44 0 0 1 .437.438a.44.44 0 0 1-.437.437a.44.44 0 0 1-.438-.437a.44.44 0 0 1 .438-.438m-2.77.463a.54.54 0 0 1 .326.156l2.006 2.006h-3.5l.598-1.794a.54.54 0 0 1 .57-.368");
}

:global(.ywbk9fbil) {
  fill-rule: evenodd;
  stroke-linecap: square;
}

</style>
