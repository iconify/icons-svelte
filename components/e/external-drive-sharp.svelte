<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ens4qpg9v"/><path class="o1zlll-zk"/><path class="horrqsboc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:external-drive-sharp" {...props}></Icon>
<style>
:global(.ens4qpg9v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75h12.5v14H5.75zm3.5 3.75h5.5");
}

:global(.horrqsboc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.75v4.5h7.25");
}

:global(.o1zlll-zk) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.25h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
