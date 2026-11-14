<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lvy3hlsgp"/><path class="x5vnkwbup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:differential-diagnosis" {...props}></Icon>
<style>
:global(.lvy3hlsgp) {
  d: path("M2.5 12H9m0 0l6-6m-6 6h6.5M9 12l6 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x5vnkwbup) {
  fill: currentColor;
  d: path("M16 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
