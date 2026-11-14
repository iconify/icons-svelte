<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aizxfybor"/><path class="esk2i4b8a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dart-sewing" {...props}></Icon>
<style>
:global(.aizxfybor) {
  d: path("M4 3.5h16V18c-2.5-2-5.5-2-8 0s-5.5 2-8 0Z");
}

:global(.esk2i4b8a) {
  d: path("m9.5 3.5l2.5 10l2.5-10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
