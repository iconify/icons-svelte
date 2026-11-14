<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="obn4d-4fi"/><path class="cid3i0bxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:account-linked" {...props}></Icon>
<style>
:global(.cid3i0bxr) {
  d: path("m15.995 16.884l3.889-3.889l2.121 2.121l-3.889 3.889Z");
}

:global(.obn4d-4fi) {
  d: path("M10.7 21.5H4.5v-19h15v6.9m-11-6.9v19m3-14.5h4m-2.505 12.884l3.889-3.889l2.121 2.121l-3.889 3.889Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
