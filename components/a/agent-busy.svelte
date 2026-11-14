<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nxxxqxbbb"/><path class="sbezkcbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:agent-busy" {...props}></Icon>
<style>
:global(.nxxxqxbbb) {
  d: path("M12.7 17.5H2.5v-12h15v6.4M10 2.5v3m-3 6h.01m5.99 0h.01m2.49 3.25h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
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
