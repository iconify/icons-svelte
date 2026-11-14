<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o28fxbufr"/><path class="z49iurbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-kayak" {...props}></Icon>
<style>
:global(.o28fxbufr) {
  d: path("M2.5 12C7 8.5 17 8.5 21.5 12C17 15.5 7 15.5 2.5 12ZM7 7l10 10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z49iurbbs) {
  fill: currentColor;
  d: path("m2.172 3.939l1.767-1.767l3.889 3.889l-1.767 1.767Zm14 14l1.767-1.767l3.889 3.889l-1.767 1.767Z");
}

</style>
