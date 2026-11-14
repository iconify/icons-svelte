<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jg_rdmb9q"/><path class="ei8we7kng"/><path class="fup-0ib7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:atom-model" {...props}></Icon>
<style>
:global(.ei8we7kng) {
  d: path("M18.75 5.25a9.5 4-45 1 1-13.5 13.5a9.5 4-45 1 1 13.5-13.5Z");
}

:global(.fup-0ib7j) {
  d: path("M10.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8.25 0h.01");
}

:global(.jg_rdmb9q) {
  d: path("M5.25 5.25a9.5 4 45 1 1 13.5 13.5a9.5 4 45 1 1-13.5-13.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
