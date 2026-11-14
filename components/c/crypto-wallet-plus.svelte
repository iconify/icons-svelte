<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wsq59ibye"/><path class="n7tqdcbab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crypto-wallet-plus" {...props}></Icon>
<style>
:global(.n7tqdcbab) {
  d: path("M21.5 7.5h-4a2 2 0 0 0 0 4h4M18 15v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wsq59ibye) {
  d: path("M12.2 19.5H2.5v-15h19v10.7");
}

</style>
