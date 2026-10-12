<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zxujzjbsj"/><path class="ypm311bxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:car-jack-sharp" {...props}></Icon>
<style>
:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ypm311bxb) {
  d: path("M4.75 12h15.5v3.75");
}

:global(.zxujzjbsj) {
  d: path("M3.75 18.75h16.5v2.5H3.75zm4.5-16h7.5v2.5h-7.5zM12 5.25L6.5 12l5.5 6.75L17.5 12Z");
}

</style>
