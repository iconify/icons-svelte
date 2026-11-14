<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uovan4nrf"/><path class="lycsx7b_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cargo-seal-number" {...props}></Icon>
<style>
:global(.lycsx7b_n) {
  d: path("M12 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 0c-6 0-8.5 2.5-8.5 6.5v6m7-8h6m-6 3H14m-3.5 3h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uovan4nrf) {
  d: path("M7.5 3.5h12v18h-12Z");
}

</style>
