<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cetgrthhr"/><path class="h5ozmlbta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fare-card-register" {...props}></Icon>
<style>
:global(.cetgrthhr) {
  d: path("M13 2.5h8.5v19H13ZM13 8h8.5");
}

:global(.h5ozmlbta) {
  d: path("M15.5 14.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-13-5H10v6H2.5Zm0 2.25H10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
