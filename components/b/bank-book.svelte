<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lgze94bco"/><path class="slbpnol2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bank-book" {...props}></Icon>
<style>
:global(.lgze94bco) {
  d: path("M3 19V5a2.5 2.5 0 0 1 2.5-2.5H13v19H5.5A2.5 2.5 0 0 1 3 19Z");
}

:global(.slbpnol2f) {
  d: path("M3 19a2.5 2.5 0 0 1 2.5-2.5H13m2.5 1l3-2.75l3 2.75m-4.5 0v4m3-4v4m-4.5 0h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
