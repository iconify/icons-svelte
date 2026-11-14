<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b3d6-pylv"/><path class="il245hbpr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coiled-snake" {...props}></Icon>
<style>
:global(.b3d6-pylv) {
  d: path("M19 20.5H6a1.5 1.5 0 0 1 0-3h11a1.5 1.5 0 0 0 0-3H9c-4 0-3-9 1.75-9");
}

:global(.il245hbpr) {
  d: path("M10.75 5.5a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0Zm5 0h2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
