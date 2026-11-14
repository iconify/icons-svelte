<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p2nu_ybuq"/><path class="mw58uovga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:carpenter-pencil" {...props}></Icon>
<style>
:global(.mw58uovga) {
  d: path("M7.05 12L12 16.95l-5.303 2.475l-2.122-2.122Zm-.707 4.243l1.414 1.414");
}

:global(.p2nu_ybuq) {
  d: path("m16.243 2.808l4.949 4.949L12 16.95L7.05 12Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
