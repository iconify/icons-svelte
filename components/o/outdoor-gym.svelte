<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rdipjixcd"/><path class="t01-m2bae"/><path class="gzjherbio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:outdoor-gym" {...props}></Icon>
<style>
:global(.gzjherbio) {
  d: path("M10.25 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM12 12.5v5m-2.25 4l2.25-4l2.25 4");
}

:global(.rdipjixcd) {
  d: path("M3.5 21.5V4h17v17.5");
}

:global(.t01-m2bae) {
  d: path("m6.5 4l2.25 8.5h6.5L17.5 4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
