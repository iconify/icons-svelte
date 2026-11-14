<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m20o5b2jc"/><path class="r166okuox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:razor-blade" {...props}></Icon>
<style>
:global(.m20o5b2jc) {
  d: path("M3.5 7h17v10h-17ZM7 12h10");
}

:global(.r166okuox) {
  d: path("M6 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm10 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
