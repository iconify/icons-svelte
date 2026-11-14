<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cxrvloiwd"/><path class="odp_qrb9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:nft-creator" {...props}></Icon>
<style>
:global(.cxrvloiwd) {
  d: path("M16.5 9.1v12.4h-14V8h11.9");
}

:global(.odp_qrb9b) {
  d: path("m5.5 18.5l3.5-4l4.5 4M18 2q0 3.5 3.5 3.5Q18 5.5 18 9q0-3.5-3.5-3.5Q18 5.5 18 2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
