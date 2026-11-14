<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j7e0p2chq"/><path class="vu-2ln_fl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:profit-center" {...props}></Icon>
<style>
:global(.j7e0p2chq) {
  d: path("M3.5 21.5V13H9V9.5h6V13h5.5v8.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vu-2ln_fl) {
  d: path("M10.25 21.5v-4h3.5v4M12 6.75V2.5M9.5 5L12 2.5L14.5 5");
}

</style>
