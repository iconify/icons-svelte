<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="he9m0nb2n"/><path class="mvml0sbjb"/><path class="x2vewobfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dead-end-sign" {...props}></Icon>
<style>
:global(.he9m0nb2n) {
  d: path("M2 2h20v15H2Zm10 15v5");
}

:global(.mvml0sbjb) {
  fill: currentColor;
  d: path("M7 4.5h10V7H7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x2vewobfi) {
  d: path("M12 7v7.5");
}

</style>
