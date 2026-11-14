<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="epqllh62y"/><path class="ejkj6th1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:account-direct-debit" {...props}></Icon>
<style>
:global(.ejkj6th1k) {
  d: path("M16.25 15.5h4.25v4.25");
}

:global(.epqllh62y) {
  d: path("M11.6 21.5H4.5v-19h15v10.1M8.5 2.5v19m3-14.5h4M15 21l5.25-5.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
