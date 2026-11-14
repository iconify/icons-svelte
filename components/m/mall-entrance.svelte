<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a5mher4uw"/><path class="gyqlmg7ct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mall-entrance" {...props}></Icon>
<style>
:global(.a5mher4uw) {
  d: path("M3.5 21.5V11a8.5 8.5 0 0 1 17 0v10.5");
}

:global(.gyqlmg7ct) {
  d: path("M7.5 21.5V13h9v8.5M12 13v8.5m-1.75-4h.01m3.49 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
