<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lvjes1b8h"/><path class="wkssh-j0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fuse-blown" {...props}></Icon>
<style>
:global(.lvjes1b8h) {
  d: path("M7 7.5h10v9H7ZM2.5 7H7v10H2.5ZM17 7h4.5v10H17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wkssh-j0u) {
  d: path("m7 12l1.75-1.5l1.75 3m3-3l1.75 3L17 12");
}

</style>
