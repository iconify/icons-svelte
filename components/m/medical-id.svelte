<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f18_f1p2j"/><path class="r202gjydl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:medical-id" {...props}></Icon>
<style>
:global(.f18_f1p2j) {
  d: path("M5.5 2.5h13v19h-13Z");
}

:global(.r202gjydl) {
  d: path("M8.5 7.5h7V15h-7ZM12 9.25v4m-2-2h4m-3.5 7.25h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
