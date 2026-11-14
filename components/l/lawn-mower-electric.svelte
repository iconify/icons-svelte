<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="te5k6e35r"/><path class="efxz7qqkp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lawn-mower-electric" {...props}></Icon>
<style>
:global(.efxz7qqkp) {
  d: path("M7.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-8.75-13C2.5 8 2 14 4 21.5");
}

:global(.te5k6e35r) {
  d: path("M6.5 17.5v-3A2.5 2.5 0 0 1 9 12h6a5.5 5.5 0 0 1 5.5 5.5Zm3-5.5l-3-9H5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
