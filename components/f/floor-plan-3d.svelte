<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fdnlxcc3s"/><path class="rnxct9jcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:floor-plan-3d" {...props}></Icon>
<style>
:global(.fdnlxcc3s) {
  d: path("m2.5 14.5l9.5-6l9.5 6l-9.5 6Z");
}

:global(.rnxct9jcs) {
  d: path("M2.5 14.5V10L12 4l9.5 6v4.5M12 4v4.5m-4.75 3l4.75 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
