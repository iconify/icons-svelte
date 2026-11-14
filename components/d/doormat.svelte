<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ozx-odbqi"/><path class="d54j_4xxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:doormat" {...props}></Icon>
<style>
:global(.d54j_4xxg) {
  d: path("M9.5 9.5H17l-2 5H7.5Z");
}

:global(.ozx-odbqi) {
  d: path("M6 6.5h15.5l-3.5 11H2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
