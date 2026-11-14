<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pvi8foxke"/><path class="r0xl7acoe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:liabilities-column" {...props}></Icon>
<style>
:global(.pvi8foxke) {
  d: path("M4.5 2.5h15v19h-15Zm3.5 4h8M8 10h5.5");
}

:global(.r0xl7acoe) {
  fill: currentColor;
  d: path("M7.25 13.5h9.5v5.25h-9.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
