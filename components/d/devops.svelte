<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h-i-7g62p"/><path class="ro9-hrbda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:devops" {...props}></Icon>
<style>
:global(.h-i-7g62p) {
  d: path("M12 12c-2.5-5-9-6-9 0s6.5 5 9 0s9-6 9 0s-6.5 5-9 0Z");
}

:global(.ro9-hrbda) {
  d: path("m15.5 6l2 2l-2 2m-11 4l2 2l-2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
