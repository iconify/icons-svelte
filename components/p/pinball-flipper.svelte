<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="czodshpft"/><path class="ks7x8fb8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pinball-flipper" {...props}></Icon>
<style>
:global(.czodshpft) {
  d: path("M4.75 14L19 7.25a1.25 1.25 0 0 1 1.25 2.25L8 19.5A3.25 3.25 0 1 1 4.75 14Z");
}

:global(.ks7x8fb8h) {
  d: path("M9 7.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM6 17h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
