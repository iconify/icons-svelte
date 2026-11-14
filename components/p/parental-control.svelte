<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ccrcypbbk"/><path class="dm_wopyrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:parental-control" {...props}></Icon>
<style>
:global(.ccrcypbbk) {
  d: path("M12.2 17.5H2.5V3h19v11M11 17.5v3m-4 0h5.2m2.8-3h6v4h-6Z");
}

:global(.dm_wopyrf) {
  d: path("M16.5 17.5v-1a1.5 1.5 0 0 1 3 0v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
