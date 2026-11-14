<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wffwdccte"/><path class="alrtihbek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:calculator-device" {...props}></Icon>
<style>
:global(.alrtihbek) {
  d: path("M7 5.5h10v4H7Zm1 8h.01m3.99 0h.01m3.99 0h.01M8 18h.01M12 18h.01M16 18h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wffwdccte) {
  d: path("M4 2.5h16v19H4Z");
}

</style>
