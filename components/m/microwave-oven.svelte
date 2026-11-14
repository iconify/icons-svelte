<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r21jxhxfq"/><path class="n8yvk5bkc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:microwave-oven" {...props}></Icon>
<style>
:global(.n8yvk5bkc) {
  d: path("M6 8h8.5v8H6Zm11 1h.01M17 12h.01");
}

:global(.r21jxhxfq) {
  d: path("M3 5h18v14H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
