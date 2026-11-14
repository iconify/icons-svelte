<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t3xf9kbbb"/><path class="quz89fb4a"/><path class="kssu0pbsm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:color-scheme" {...props}></Icon>
<style>
:global(.kssu0pbsm) {
  d: path("m17.556 9.641l1.881 5.168l-14.096 5.13l-1.881-5.168ZM6.75 16.5h.01");
}

:global(.quz89fb4a) {
  d: path("m11.667 4.683l4.505 3.155l-8.603 12.287l-4.506-3.154Z");
}

:global(.t3xf9kbbb) {
  d: path("M4 4h5.5v15H4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
