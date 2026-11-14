<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zpubw_bok"/><path class="l52be5f2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:queue-empty" {...props}></Icon>
<style>
:global(.l52be5f2m) {
  d: path("M3 12.5h5.5L10 15h4l1.5-2.5H21");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zpubw_bok) {
  d: path("m3 12.5l3-8h12l3 8v5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>
