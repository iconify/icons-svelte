<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qsszfyb-e"/><path class="n3znf-b1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:field-hospital" {...props}></Icon>
<style>
:global(.n3znf-b1o) {
  d: path("M5.5 8h12l4 11.5h-14m6.75-8.75v6m-3-3h6M17.5 8l4-2.5");
}

:global(.qsszfyb-e) {
  d: path("M2.5 19.5L5.5 8l2 11.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
