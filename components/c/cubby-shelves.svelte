<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hdc4j_jfs"/><path class="j7tyhbbpo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cubby-shelves" {...props}></Icon>
<style>
:global(.hdc4j_jfs) {
  d: path("M3 3h18v18H3Zm9 0v18m-9-9h18");
}

:global(.j7tyhbbpo) {
  d: path("M14.5 15.75h4V21h-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
