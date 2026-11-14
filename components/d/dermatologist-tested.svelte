<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xxwynxb5b"/><path class="gbg-obbdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dermatologist-tested" {...props}></Icon>
<style>
:global(.gbg-obbdc) {
  d: path("m8 12.25l3 3l5-5.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xxwynxb5b) {
  d: path("M4.5 5C8 5 10 4 12 2.5C14 4 16 5 19.5 5v6c0 5-3 8.5-7.5 10.5c-4.5-2-7.5-5.5-7.5-10.5Z");
}

</style>
