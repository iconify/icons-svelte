<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mz2tx1yoa"/><path class="pb4zaqboa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bond-certificate" {...props}></Icon>
<style>
:global(.mz2tx1yoa) {
  d: path("M4.5 2.5h15v13h-15Zm3.5 4h8M8 9.75h4");
}

:global(.pb4zaqboa) {
  d: path("M9 15.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm1.5 2.5l-1 3.5m4-3.5l1 3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
