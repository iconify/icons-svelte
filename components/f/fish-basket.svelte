<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gi09erb1h"/><path class="hp4xdfb_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fish-basket" {...props}></Icon>
<style>
:global(.gi09erb1h) {
  d: path("M4 11h16l-1.5 8.5q-.25 1.5-2 1.5h-9q-1.75 0-2-1.5Zm-.5 0a8.5 8.5 0 0 1 17 0");
}

:global(.hp4xdfb_w) {
  d: path("m11 11l.5-1.5l-2.5-3q3 1.5 6 0l-2.5 3L13 11m-8 4.75h14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
