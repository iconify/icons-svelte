<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pd_61dbpc"/><path class="b5kf35hxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:baby" {...props}></Icon>
<style>
:global(.b5kf35hxf) {
  d: path("M9.5 15.5c1.25 1.25 3.75 1.25 5 0M12 2.5c-1.5 1.5-1.25 3.5.5 3.75");
}

:global(.pd_61dbpc) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM9 12h.01M15 12h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
