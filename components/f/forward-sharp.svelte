<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n-xf2ebup"/><path class="q0cubz-en"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:forward-sharp" {...props}></Icon>
<style>
:global(.n-xf2ebup) {
  d: path("m14.75 5.25l5.5 5.5l-5.5 5.5");
}

:global(.q0cubz-en) {
  d: path("M20.25 10.75h-9.5a7 7 0 0 0-7 7v1");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
