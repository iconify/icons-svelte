<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sd95s0tfn"/><path class="n4irr_q9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:film-roll-35mm" {...props}></Icon>
<style>
:global(.n4irr_q9q) {
  d: path("M11 17.5h10.5v3.25H14M9.5 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM12.75 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-6.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.sd95s0tfn) {
  d: path("M3.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
