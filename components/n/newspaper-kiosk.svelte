<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="igixmxb1p"/><path class="k-4movitg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:newspaper-kiosk" {...props}></Icon>
<style>
:global(.igixmxb1p) {
  d: path("m2.5 7.5l19-4.75M4.5 7v14h15V3.25M4.5 14h15");
}

:global(.k-4movitg) {
  d: path("M8.5 14v-3.5l3.5 1l3.5-1V14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
