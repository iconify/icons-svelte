<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u007blnnp"/><path class="mr2a-eb6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pilgrim-hat" {...props}></Icon>
<style>
:global(.mr2a-eb6v) {
  d: path("M10 9.5h4V14h-4Zm-2.5 2.25H10m4 0h2.5");
}

:global(.u007blnnp) {
  d: path("M7 18.5L8 5h8l1 13.5m-14.5 0h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
