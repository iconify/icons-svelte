<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="coo_kxb_f"/><path class="j0vjosbzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-split-down" {...props}></Icon>
<style>
:global(.coo_kxb_f) {
  d: path("M12 3.5V9c0 3-5 3-5 6.5V20m5-11c0 3 5 3 5 6.5V20");
}

:global(.j0vjosbzs) {
  d: path("m4 17l3 3l3-3m4 0l3 3l3-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
