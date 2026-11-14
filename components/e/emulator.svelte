<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j9oj0xj6k"/><path class="vjzi9_byq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:emulator" {...props}></Icon>
<style>
:global(.j9oj0xj6k) {
  d: path("M12.2 15H2.5V3h17v5.2M11 15v4m-4 0h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vjzi9_byq) {
  d: path("m5.5 6l2 2l-2 2m4 0H12m3 1h6.5v11H15Z");
}

</style>
