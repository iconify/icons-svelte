<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zao27lbio"/><path class="vefgkpbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heating-zone" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vefgkpbzh) {
  d: path("M12 16q-1.25-1.25 0-2.5t0-2.5t0-2.5");
}

:global(.zao27lbio) {
  d: path("M2.5 4h19v16h-19ZM8 4v10m8-4v10");
}

</style>
