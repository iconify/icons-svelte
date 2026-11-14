<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q48u6bcup"/><path class="jzbk7yk3p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:party-shop" {...props}></Icon>
<style>
:global(.jzbk7yk3p) {
  d: path("M7.25 13q-1.25 3 .5 5.5t.5 3M13 13h8.5v8.5H13Zm4.25 0v8.5m0-8.5C15.5 9.5 13.5 11.5 15 13m2.25 0C19 9.5 21 11.5 19.5 13");
}

:global(.q48u6bcup) {
  d: path("M3 7.75a4.25 5.25 0 1 0 8.5 0a4.25 5.25 0 1 0-8.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
