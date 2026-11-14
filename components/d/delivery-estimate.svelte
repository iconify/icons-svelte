<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pz_8vmb6j"/><path class="x4h68jbhs"/><path class="sbezkcbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:delivery-estimate" {...props}></Icon>
<style>
:global(.pz_8vmb6j) {
  d: path("M12.7 19.5H2.5V3h17v8.9M2.5 8h17M11 3v5m4.5 6.75h5m-5 6.5h5");
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
