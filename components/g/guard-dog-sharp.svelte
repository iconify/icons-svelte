<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="swx5hqb0o"/><path class="fdgleknxc"/><path class="fec6d0rij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:guard-dog-sharp" {...props}></Icon>
<style>
:global(.fdgleknxc) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 10h.01");
}

:global(.fec6d0rij) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 18.25h7.75");
}

:global(.swx5hqb0o) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 21.25V14.5l-2.25-1.875V9.5l.75-6l3.25 3H14l1.75 1.75l1.5 1.5h4v4.5H15.5l-1.25 1.5v5.5Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
