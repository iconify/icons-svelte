<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kz__4hbfi"/><path class="qx5ch8hoz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coral-nursery" {...props}></Icon>
<style>
:global(.kz__4hbfi) {
  d: path("M3.5 7.5h17v14h-17ZM3 4q2.25-1.5 4.5 0T12 4t4.5 0T21 4m-9 3.5V18");
}

:global(.qx5ch8hoz) {
  d: path("m12 10.5l-3.25 2.75v3.25m3.25-3l3.25 2.75V19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
