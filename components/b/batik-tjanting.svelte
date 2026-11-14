<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gtdtfrzlu"/><path class="csx4t6b2j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:batik-tjanting" {...props}></Icon>
<style>
:global(.csx4t6b2j) {
  d: path("M16 11.5q0 3.5-2.5 5.5m-.5 3h.01");
}

:global(.gtdtfrzlu) {
  d: path("M12 4.5h8v3a4 4 0 0 1-8 0ZM2.5 6H12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
