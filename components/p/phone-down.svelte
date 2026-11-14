<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vnxnuacte"/><path class="efz-9di1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:phone-down" {...props}></Icon>
<style>
:global(.efz-9di1o) {
  d: path("m15 18.5l3 3l3-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vnxnuacte) {
  d: path("M14.1 21.5H5v-19h13v9.2m-8-6.2h3m5 9v7");
}

</style>
