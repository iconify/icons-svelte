<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mahfh0bnb"/><path class="jyt8ctbbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:computer-shop" {...props}></Icon>
<style>
:global(.jyt8ctbbw) {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 20.5v-5h4v5m4.25-5.5h7v5h-7Zm3.5 5v2m-2 0h4");
}

:global(.mahfh0bnb) {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v1.2M4.5 11v9.5h7.4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
