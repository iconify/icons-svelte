<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ee7fr_buz"/><path class="r0opx9bnv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:funny-car" {...props}></Icon>
<style>
:global(.ee7fr_buz) {
  d: path("M3.5 14v-3H9l2.5-3H14l2.5 3l5 1.25V14Zm2-3V5.5m-3 0H8");
}

:global(.r0opx9bnv) {
  d: path("M4.5 16.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM16 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
