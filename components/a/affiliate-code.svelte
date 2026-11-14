<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tbj3gibyf"/><path class="thk7qg-cz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:affiliate-code" {...props}></Icon>
<style>
:global(.tbj3gibyf) {
  d: path("M2.5 12L9 4.5h12v15H9Z");
}

:global(.thk7qg-cz) {
  d: path("M6.25 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm6.25 4.5l5.5-9M13 9h.01m4.49 6h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
