<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bi9htujil"/><path class="nwjh2jbvu"/><path class="hn8y3497e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fare-card-refund" {...props}></Icon>
<style>
:global(.bi9htujil) {
  d: path("M6.5 8.5h11v7h-11Zm0 2.5h11");
}

:global(.hn8y3497e) {
  d: path("m3.5 3.75l.25 3.5L7 5.75");
}

:global(.nwjh2jbvu) {
  d: path("M7.25 20.25a9.5 9.5 0 1 0-3.5-13");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
