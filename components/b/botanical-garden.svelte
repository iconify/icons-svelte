<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h3_4q0bmq"/><path class="fy-i81bly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:botanical-garden" {...props}></Icon>
<style>
:global(.fy-i81bly) {
  d: path("M12 15.5c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4Zm0-2c0-2.5 1.5-4 4-4c0 2.5-1.5 4-4 4Z");
}

:global(.h3_4q0bmq) {
  d: path("M3.5 21V11a8.5 8.5 0 0 1 17 0v10Zm8.5-.5v-7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
