<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jrn0f9x9o"/><path class="lp4ys-yru"/><path class="sbezkcbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:oven-timer" {...props}></Icon>
<style>
:global(.jrn0f9x9o) {
  d: path("M12.7 19.5H2.5v-17h17v9.4M2.5 8h17M6 5.25h.01m3.49 0h.01");
}

:global(.lp4ys-yru) {
  d: path("M5.5 10.75h7v5h-7Zm10 4h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
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

</style>
