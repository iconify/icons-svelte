<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ha-dbsbzk"/><path class="v4d4_sb8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:check-triangle" {...props}></Icon>
<style>
:global(.ha-dbsbzk) {
  d: path("m12 2.5l9.75 18.25H2.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v4d4_sb8y) {
  d: path("M8.25 15.75L10.5 18l4-4.75");
}

</style>
