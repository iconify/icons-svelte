<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qa7jj2b-r"/><path class="rii8zpwwj"/><path class="qoyr22bud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:join-inner" {...props}></Icon>
<style>
:global(.qa7jj2b-r) {
  d: path("M2.5 2.5H15V15H2.5Z");
}

:global(.qoyr22bud) {
  fill: currentColor;
  d: path("M9 11a2 2 0 0 1 2-2h4v4a2 2 0 0 1-2 2H9Z");
}

:global(.rii8zpwwj) {
  d: path("M9 9h12.5v12.5H9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
