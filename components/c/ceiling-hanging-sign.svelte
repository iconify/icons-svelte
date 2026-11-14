<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tge2xqzyj"/><path class="xid91tbpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ceiling-hanging-sign" {...props}></Icon>
<style>
:global(.tge2xqzyj) {
  d: path("M2.5 2.5h19M6 2.5v6m12-6v6m-15.5 0h19V19h-19ZM7 13.75h9.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xid91tbpa) {
  d: path("m13.75 11l2.75 2.75l-2.75 2.75");
}

</style>
