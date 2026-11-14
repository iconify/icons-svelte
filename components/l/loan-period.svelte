<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ka2d7gber"/><path class="x4h68jbhs"/><path class="sbezkcbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:loan-period" {...props}></Icon>
<style>
:global(.ka2d7gber) {
  d: path("M12.7 19.5H3v-16h16v8.4M7.5 2.5V6m7-3.5V6M3 9h16m-3.5 5.75h5m-5 6.5h5");
}

:global(.sbezkcbzn) {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x4h68jbhs) {
  d: path("M16.5 14.75v1l3 4.5v1");
}

</style>
