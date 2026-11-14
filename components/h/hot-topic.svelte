<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hpkep8bsv"/><path class="es7oatblx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hot-topic" {...props}></Icon>
<style>
:global(.es7oatblx) {
  d: path("M12 15.5c-1.75 0-3.25-1.25-3.25-2.75c0-2 1.75-2.75 2.25-4.75c.5.5 1 1.5 1 2.5c.75-.5 1.25-1 1.25-1.75c1.25 1 2 2.25 2 4c0 1.5-1.5 2.75-3.25 2.75Z");
}

:global(.hpkep8bsv) {
  d: path("m7.5 19.5l-3.5 1L5 17a8.5 8.5 0 1 1 2.5 2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
