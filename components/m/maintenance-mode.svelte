<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnosjpuna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:maintenance-mode" {...props}></Icon>
<style>
:global(.tnosjpuna) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5h19v7h-19Zm3.5 7V21m12-7.5V21M6 3v3.5M18 3v3.5m-9 7l2.5-7m1 7l2.5-7");
}

</style>
