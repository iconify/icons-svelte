<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o-kgtwu2h"/><path class="l29x5xuij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ab-flag" {...props}></Icon>
<style>
:global(.l29x5xuij) {
  d: path("M4.75 16.5L7 7.5l2.25 9m-3.5-3h2.5m6.5 3v-9h2a2 2 0 0 1 0 4h-2m2 0a2.5 2.5 0 0 1 0 5h-2");
}

:global(.o-kgtwu2h) {
  d: path("M2 4h20v16H2Zm10 0v16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
