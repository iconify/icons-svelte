<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eeuu98bgf"/><path class="q2tukqepe"/><path class="h02_xus3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cover-level-standard" {...props}></Icon>
<style>
:global(.eeuu98bgf) {
  d: path("M3 15h4.25v6H3Z");
}

:global(.h02_xus3y) {
  d: path("M17 3.5h4.25V21H17Z");
}

:global(.q2tukqepe) {
  fill: currentColor;
  d: path("M10 9.5h4.25V21H10Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
