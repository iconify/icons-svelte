<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ej8w_zqvu"/><path class="xiuxu4a9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cone" {...props}></Icon>
<style>
:global(.ej8w_zqvu) {
  d: path("M12 3L4.5 17.5a7.5 3 0 0 0 15 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xiuxu4a9r) {
  d: path("M4.5 17.5a7.5 3 0 0 1 15 0");
}

</style>
