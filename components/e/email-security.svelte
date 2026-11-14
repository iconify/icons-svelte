<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zie8fnb0n"/><path class="j0521ysgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:email-security" {...props}></Icon>
<style>
:global(.j0521ysgu) {
  d: path("m2.5 7l8.75 5.5L20 7m-5 10.5h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zie8fnb0n) {
  d: path("M12.2 18.5H2.5v-14H20v8.2");
}

</style>
