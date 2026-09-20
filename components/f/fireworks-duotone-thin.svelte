<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bjzalvuax"/><path class="ttlgpt4th"/><path class="llo2dh__w"/><path class="z3ry47brx"/><path class="djfn01-wc"/><path class="qyws9lb8n"/><path class="ux6apgnet"/><path class="u6ltz0bsa"/><path class="z5j-qdr3m"/><path class="hsrzt0bgt"/><path class="o5ex3bb1u"/><path class="lnxxf4b_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fireworks-duotone-thin" {...props}></Icon>
<style>
:global(.bjzalvuax) {
  fill: currentColor;
  d: path("M7 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.djfn01-wc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 8 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsrzt0bgt) {
  d: path("m10 8 3 -3");
}

:global(.llo2dh__w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 7V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lnxxf4b_g) {
  d: path("m19 19 2 2");
}

:global(.o5ex3bb1u) {
  d: path("M16 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qyws9lb8n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 19 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ttlgpt4th) {
  fill: currentColor;
  d: path("M16 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u6ltz0bsa) {
  d: path("M8 7V4");
}

:global(.ux6apgnet) {
  d: path("M7 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.z3ry47brx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8 3 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z5j-qdr3m) {
  d: path("M6 8 3 5");
}

</style>
