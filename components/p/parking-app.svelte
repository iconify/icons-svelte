<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f8dhrmbma"/><path class="e3od_zb8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:parking-app" {...props}></Icon>
<style>
:global(.e3od_zb8f) {
  d: path("M10 7h2.5a2.75 2.75 0 0 1 0 5.5H10");
}

:global(.f8dhrmbma) {
  d: path("M6 2.5h12v19H6ZM10 17V7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
