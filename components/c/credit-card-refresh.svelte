<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jn6f_02ks"/><path class="d_lxe3nhn"/><path class="bc_zdk5yy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:credit-card-refresh" {...props}></Icon>
<style>
:global(.bc_zdk5yy) {
  d: path("m16.75 14.25l1.5 1.25l-1.5 1.25");
}

:global(.d_lxe3nhn) {
  d: path("M21 18.25a2.75 2.75 0 1 1-2.75-2.75");
}

:global(.jn6f_02ks) {
  d: path("M12.7 19H2.5V5h19v9.6m-19-5.1h19m-19 0h19M6 15h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
