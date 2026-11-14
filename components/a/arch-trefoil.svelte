<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tllw2iado"/><path class="mukpw2btv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arch-trefoil" {...props}></Icon>
<style>
:global(.mukpw2btv) {
  d: path("M9.75 9.5a2.5 2.5 0 1 1 4.5 0A2.5 2.5 0 1 1 12 13.25A2.5 2.5 0 1 1 9.75 9.5Z");
}

:global(.tllw2iado) {
  d: path("M4.5 21.5v-11a7.5 7.5 0 0 1 15 0v11M3 21.5h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
