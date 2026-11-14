<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kxpl5yjdd"/><path class="sz9fs5h8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:plum-tree" {...props}></Icon>
<style>
:global(.kxpl5yjdd) {
  d: path("M13.124 16.5H4l4.5-7h-2l5.5-7l5.5 7h-2l1.567 2.438M12 16.5v5m3.5-2.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

:global(.sz9fs5h8t) {
  d: path("M18.25 16q0-2 1.75-2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
