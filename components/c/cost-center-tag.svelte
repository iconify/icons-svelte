<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hmemhacds"/><path class="zmh-2ludh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cost-center-tag" {...props}></Icon>
<style>
:global(.hmemhacds) {
  d: path("M8.5 5.5h12v13h-12l-5-6.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zmh-2ludh) {
  d: path("M7 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.75 0H17");
}

</style>
