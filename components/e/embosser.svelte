<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aivl7gmbz"/><path class="c2h6t2r3b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:embosser" {...props}></Icon>
<style>
:global(.aivl7gmbz) {
  d: path("M2.5 15.5h19v4h-19Zm3 0v-8a3 3 0 0 1 3-3H20m-4 0V8");
}

:global(.c2h6t2r3b) {
  d: path("M12.5 8h7v3.5h-7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
