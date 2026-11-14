<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eztpt9bdu"/><path class="m93mnfbwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:festival-chariot" {...props}></Icon>
<style>
:global(.eztpt9bdu) {
  d: path("m6 13l1.75-4h1.5l1.25-3.5L12 3l1.5 2.5L14.75 9h1.5L18 13M4 13h16v3H4Z");
}

:global(.m93mnfbwt) {
  d: path("M4.75 18.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm9 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
