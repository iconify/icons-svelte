<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xfr1zeb6q"/><path class="bfj_46lvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:digital-kiosk" {...props}></Icon>
<style>
:global(.bfj_46lvz) {
  d: path("M9.75 5.25h4.5v6.5h-4.5ZM10 15.5h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xfr1zeb6q) {
  d: path("M7 21.5v-17a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v17m-12.5 0h15");
}

</style>
