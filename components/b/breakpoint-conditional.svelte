<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wqaej5m_a"/><path class="zu3gggu0t"/><path class="wp-iwphvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:breakpoint-conditional" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wp-iwphvr) {
  d: path("M15.5 16a2.5 2.5 0 1 1 3.5 2.25c-.75.25-1 .75-1 1.5M18 22h.01");
}

:global(.wqaej5m_a) {
  d: path("M2.5 8.5h17");
}

:global(.zu3gggu0t) {
  fill: currentColor;
  d: path("M5 8.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

</style>
