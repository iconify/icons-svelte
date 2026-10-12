<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fha6990wp"/><path class="myuvscn1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:prompt-template-sharp" {...props}></Icon>
<style>
:global(.fha6990wp) {
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

:global(.myuvscn1x) {
  d: path("M9 8.25H7.25v2.5l-1 1.25l1 1.25v2.5H9m6-7.5h1.75v2.5l1 1.25l-1 1.25v2.5H15M10.75 12h2.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
