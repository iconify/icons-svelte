<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="excek_s5g"/><path class="ebuv5l2qm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:insulin-pump" {...props}></Icon>
<style>
:global(.ebuv5l2qm) {
  d: path("M5 5.5h7.5v4H5Zm7 7.5c0 3.5-3.5 3.5-3.5 6c0 2.25 4 2.5 6.75.5m.5-1.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm2.75 0h.01");
}

:global(.excek_s5g) {
  d: path("M2.5 3H15v10H2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
