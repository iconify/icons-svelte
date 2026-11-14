<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="esx38kbtw"/><path class="i1sjx7bzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:clay-tablet" {...props}></Icon>
<style>
:global(.esx38kbtw) {
  d: path("m4.311 3.992l12.873-1.809l2.505 17.825l-12.873 1.809Z");
}

:global(.i1sjx7bzd) {
  d: path("m7.699 6.545l.348 2.476l6.758-2.212Zm.661 4.704l.348 2.476l5.273-2.003Zm.661 4.704l.348 2.476l6.758-2.212Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
