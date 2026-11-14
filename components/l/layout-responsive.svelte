<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="itls3g7-o"/><path class="os4oa5b-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:layout-responsive" {...props}></Icon>
<style>
:global(.itls3g7-o) {
  d: path("M11 14.5H4.5a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2");
}

:global(.os4oa5b-i) {
  d: path("M14 8.5h7.5V21H14Zm-7 6v4m-2.5 0h5m7.25-.5h2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
