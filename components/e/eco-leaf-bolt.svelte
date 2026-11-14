<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pl2itdlzc"/><path class="ju31zcb1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eco-leaf-bolt" {...props}></Icon>
<style>
:global(.ju31zcb1h) {
  d: path("m13 7l-4.5 6H12l-1 4.5l4.5-6H12Z");
}

:global(.pl2itdlzc) {
  d: path("M4 20C3 11 8 3.5 20 3.5C20.5 15 14 21 4 20Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
