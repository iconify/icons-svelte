<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qakfjpo1e"/><path class="wphvxrb5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:category-jewelry" {...props}></Icon>
<style>
:global(.qakfjpo1e) {
  d: path("M8 4h8l4 5.5L12 21L4 9.5ZM4 9.5h16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wphvxrb5q) {
  d: path("M12 21L9 9.5L11 4");
}

</style>
