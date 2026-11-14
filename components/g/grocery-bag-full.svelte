<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f0ng-_-es"/><path class="bsolnvcgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:grocery-bag-full" {...props}></Icon>
<style>
:global(.bsolnvcgy) {
  d: path("m5.61 3.144l2.898-.777l1.941 7.245l-2.898.776ZM14 10c0-3 1.5-5.25 4.5-6c.5 3-1.25 5.25-4.5 6");
}

:global(.f0ng-_-es) {
  d: path("M5 10h14v11H5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
