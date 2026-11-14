<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nig8nvb1k"/><path class="e9diypbaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:map-report-issue" {...props}></Icon>
<style>
:global(.e9diypbaj) {
  d: path("m17.5 12l4.5 9.75h-9Zm0 3.75v2m0 2h.01");
}

:global(.nig8nvb1k) {
  d: path("M11.033 19.224L8.5 18.5l-6 2v-15l6-2l7 2l6-2v10.571M9 3.5V18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
