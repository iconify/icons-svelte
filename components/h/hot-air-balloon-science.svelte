<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q6ph0oj_s"/><path class="cgnyx9bkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hot-air-balloon-science" {...props}></Icon>
<style>
:global(.cgnyx9bkt) {
  d: path("M12 2.5c-4.5 3.5-3.5 10-2.5 13m2.5-13c4.5 3.5 3.5 10 2.5 13m-5 0v2.75m5-2.75v2.75");
}

:global(.q6ph0oj_s) {
  d: path("M9.5 15.5c-2.75-2-4.25-4-4.25-6.25a6.75 6.75 0 0 1 13.5 0c0 2.25-1.5 4.25-4.25 6.25Zm0 2.75h5v3.25h-5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
