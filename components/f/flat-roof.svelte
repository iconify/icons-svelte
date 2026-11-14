<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bmj7y3blv"/><path class="tf3uaub_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flat-roof" {...props}></Icon>
<style>
:global(.bmj7y3blv) {
  d: path("M2.5 4h19v3h-19Zm2 3v14.5h15V7");
}

:global(.tf3uaub_f) {
  d: path("M10.5 21.5v-5h3v5M7 9.75h10v3.5H7Zm5 0v3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
