<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nkpgljbdx"/><path class="ckqz40b-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cracked-house-sharp" {...props}></Icon>
<style>
:global(.ckqz40b-o) {
  d: path("m14 4.68l-3 4.57l3 3l-2.75 4l1.5 2.5");
}

:global(.nkpgljbdx) {
  d: path("m12.38 3.32l8.49 7.11l.38.32h-2v10.5H4.75v-10.5h-2l.38-.32l8.49-7.11L12 3z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
