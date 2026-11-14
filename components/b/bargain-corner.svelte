<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wl672wo-l"/><path class="nvhu3tbsu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bargain-corner" {...props}></Icon>
<style>
:global(.nvhu3tbsu) {
  d: path("m13.75 6.25l2.009 2.65l3.294-.453l-.453 3.294l2.65 2.009l-2.65 2.009l.453 3.294l-3.294-.453l-2.009 2.65l-2.009-2.65l-3.294.453l.453-3.294l-2.65-2.009l2.65-2.009l-.453-3.294l3.294.453Zm-2.5 10l5-5m-4.75.25h.01M16 16h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wl672wo-l) {
  d: path("M3 21.5V3h18.5");
}

</style>
