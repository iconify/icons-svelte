<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hi5ydxdws"/><path class="gq9gvxuzc"/><path class="uggczyo5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:age-pin" {...props}></Icon>
<style>
:global(.gq9gvxuzc) {
  d: path("M12.75 13.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.hi5ydxdws) {
  d: path("M7.5 9V7a4.5 4.5 0 0 1 9 0v2M3 9h18v12.5H3Zm6 2.75v7");
}

:global(.uggczyo5f) {
  d: path("M12.75 17a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
