<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j6id6fxzf"/><path class="a-qng6b-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:engine-shed" {...props}></Icon>
<style>
:global(.a-qng6b-l) {
  d: path("M5.5 21v-8h6.9m2.85 1.25h6.5v7h-6.5Zm0 3.25h6.5");
}

:global(.j6id6fxzf) {
  d: path("M12.401 21H2.5V10L12 3l9.5 7v1.499");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
