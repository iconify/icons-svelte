<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="faob-wbmi"/><path class="h249a1xyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:post-collab" {...props}></Icon>
<style>
:global(.faob-wbmi) {
  d: path("M2.5 2.5h12v12h-12Z");
}

:global(.h249a1xyk) {
  d: path("M9.5 9.5h12v12h-12ZM6 6.5h5m2 11h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
