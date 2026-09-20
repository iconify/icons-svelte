<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkg_kabnx"/><path class="qnmmmsbha"/><path class="n7wfhbrgu"/><path class="scmqkut_d"/><path class="ngm_e1bgi"/><path class="jdz429b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-recall-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.scmqkut_d) {
  d: path("m16 5.5 2 2 3 -3");
}

:global(.tkg_kabnx) {
  d: path("M3 5h11");
}

</style>
