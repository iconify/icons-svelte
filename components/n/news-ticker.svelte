<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yjb1udbhb"/><path class="n4rqmccip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:news-ticker" {...props}></Icon>
<style>
:global(.n4rqmccip) {
  d: path("M12.5 9.5L15 12l-2.5 2.5m3.5-5l2.5 2.5l-2.5 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yjb1udbhb) {
  d: path("M2.5 6.5h19v11h-19Zm3 5.5h4");
}

</style>
