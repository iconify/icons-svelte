<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ce1tk347n"/><path class="l551_rgox"/><path class="miq9nebuq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ballot-paper-pen" {...props}></Icon>
<style>
:global(.ce1tk347n) {
  d: path("M12.3 19H3.5V2.5H18v8.9");
}

:global(.l551_rgox) {
  d: path("M7 6h5.5v5.5H7Z");
}

:global(.miq9nebuq) {
  d: path("m8.5 8.75l1.5 1.5l4.5-4.75M7 15h4m3.745 5.755l.707-2.828l4.243-4.243l2.121 2.121l-4.243 4.243Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
