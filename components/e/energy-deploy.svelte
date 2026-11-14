<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v_mocaciz"/><path class="y1v_xr-xm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:energy-deploy" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v_mocaciz) {
  d: path("M12.1 20H3.5V5.5h10v7.2m0 5.6v.3m-7-15.85h4");
}

:global(.y1v_xr-xm) {
  d: path("m10 8.5l-3 4h3.5l-2.5 4m7 4.5l5.25-5.25m-4-.25h4.25v4.25");
}

</style>
