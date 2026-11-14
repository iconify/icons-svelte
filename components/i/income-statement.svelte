<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bk0k2jhku"/><path class="wvvi3ue9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:income-statement" {...props}></Icon>
<style>
:global(.bk0k2jhku) {
  d: path("M4.5 2.5h15v19h-15ZM8 6h8M8 9.5h5.5M8 13h8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wvvi3ue9k) {
  d: path("M8 15.75h8v3H8Z");
}

</style>
