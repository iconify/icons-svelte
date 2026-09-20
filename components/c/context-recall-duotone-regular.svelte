<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cc4aslbnx"/><path class="wxx-lxpns"/><path class="xvakw33rf"/><path class="rfdy9kbzq"/><path class="e2iooachl"/><path class="ntaw4cz8x"/><path class="tkg_kabnx"/><path class="qnmmmsbha"/><path class="n7wfhbrgu"/><path class="scmqkut_d"/><path class="ngm_e1bgi"/><path class="jdz429b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-recall-duotone-regular" {...props}></Icon>
<style>
:global(.cc4aslbnx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e2iooachl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 11.5 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jdz429b-z) {
  d: path("m16 17.5 2 2 3 -3");
}

:global(.n7wfhbrgu) {
  d: path("M3 17h11");
}

:global(.ngm_e1bgi) {
  d: path("m16 11.5 2 2 3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ntaw4cz8x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 17.5 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.rfdy9kbzq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 5.5 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.scmqkut_d) {
  d: path("m16 5.5 2 2 3 -3");
}

:global(.tkg_kabnx) {
  d: path("M3 5h11");
}

:global(.wxx-lxpns) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xvakw33rf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
