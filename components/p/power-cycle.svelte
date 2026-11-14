<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oaf0dvc-u"/><path class="y9anvskex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:power-cycle" {...props}></Icon>
<style>
:global(.oaf0dvc-u) {
  d: path("M16 6a8 8 0 1 1-8 0m4-3.5V11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9anvskex) {
  d: path("M5 5.25L8 6l-.75 3");
}

</style>
