<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e96yj_bnh"/><path class="uxxqn-w9a"/><path class="ftd3zzbdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cobrowse" {...props}></Icon>
<style>
:global(.e96yj_bnh) {
  d: path("M6.5 16.5h-2a2 2 0 0 1-2-2v-10a2 2 0 0 1 2-2H15a2 2 0 0 1 2 2v2");
}

:global(.ftd3zzbdq) {
  d: path("m11 12.75l5.5 2l-2.5 1l-1.25 2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uxxqn-w9a) {
  d: path("M6.5 6.5h15V21h-15Zm0 3.5h15");
}

</style>
