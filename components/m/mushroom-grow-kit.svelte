<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o4oc42bwf"/><path class="k0qfvcbfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mushroom-grow-kit" {...props}></Icon>
<style>
:global(.k0qfvcbfs) {
  d: path("M8.5 14a3.5 3.5 0 0 1 7 0Zm3.5 0v4.5");
}

:global(.o4oc42bwf) {
  d: path("M6 2.5h12v3l1.5 3v11a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2v-11l1.5-3Zm0 3h12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
