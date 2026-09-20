<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGmljMiqUq" x1="146.49" x2="146.49" y1="175.44" y2="102.15" gradientTransform="scale(.98983 1.01027)" gradientUnits="userSpaceOnUse"><stop offset="0%" class="n1r15jqdn"/><stop offset="100%" class="dzp654dku"/></linearGradient></defs><g class="bi12bsetm"><path class="eswc4xb2s"/><path class="hlp7f2b-a"/><path class="ul47ormcp"/><path fill="url(#SVGmljMiqUq)" transform="translate(-2.7 -1.8)scale(.13592)" class="ibb415b5b"/><path class="rv2mmbx2q"/><g transform="translate(7.76 10.7)scale(.13592)" class="yk2ba6b1p"><circle class="me86ccc_a"/><circle class="rtuto4nzw"/><circle class="vp2m39b7u"/><circle class="ksunzyzhg"/><circle class="etrrpvbyh"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-madge" {...props}></Icon>
<style>
:global(.bi12bsetm) {
  fill: none;
  fill-rule: evenodd;
}

:global(.dzp654dku) {
  stop-color: var(--svg-color--4b114a, #4b114a);
}

:global(.eswc4xb2s) {
  fill: var(--svg-color--c4baff, #c4baff);
  d: path("M16.25 8.03L22.13 30H10.37z");
}

:global(.etrrpvbyh) {
  cy: 116px;
  r: 3px;
}

:global(.hlp7f2b-a) {
  fill: var(--svg-color--6750e5, #6750e5);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M23.7 2L10.34 30h18.24z");
}

:global(.ibb415b5b) {
  d: path("M85.73 220H64.31L93.19 72.48l47.1 106.64l48.79-106.64L215.03 220h-21.24l-13.24-82.82l-40.61 89.13l-39.46-89.22z");
}

:global(.ksunzyzhg) {
  cx: 125px;
  cy: 116px;
  r: 3px;
}

:global(.me86ccc_a) {
  cx: 19px;
  cy: 16px;
  r: 3px;
}

:global(.n1r15jqdn) {
  stop-color: var(--svg-color--803fa5, #803fa5);
}

:global(.rtuto4nzw) {
  cx: 63px;
  cy: 110px;
  r: 3px;
}

:global(.rv2mmbx2q) {
  stroke: var(--svg-color--a28bca, #a28bca);
  stroke-linecap: square;
  stroke-opacity: 0.36;
  stroke-width: var(--svg-stroke-width--0-27px, 0.27px);
  d: path("m7.83 26.13l2.45-13.19m5.91 12.3L10.35 12.6m6.11 12.5l5.98-12.5m2.25 13.8l-2.25-13.53");
}

:global(.ul47ormcp) {
  fill: var(--svg-color--6750e5, #6750e5);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m9.04 2l13.12 28H3.4z");
}

:global(.vp2m39b7u) {
  cx: 108px;
  cy: 16px;
  r: 3px;
}

:global(.yk2ba6b1p) {
  fill: var(--svg-color--dcc6ff, #dcc6ff);
}

</style>
