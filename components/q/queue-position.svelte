<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w2ot_ibqo"/><path class="f6_kdhrvp"/><path class="ef1k80gsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:queue-position" {...props}></Icon>
<style>
:global(.ef1k80gsz) {
  d: path("M9 17.5h12v3H9Zm-6-8L5.5 12L3 14.5");
}

:global(.f6_kdhrvp) {
  fill: currentColor;
  d: path("M9 10.5h12v3H9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w2ot_ibqo) {
  d: path("M9 3.5h12v3H9Z");
}

</style>
