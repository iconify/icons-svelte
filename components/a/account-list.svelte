<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hes_-lb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:account-list" {...props}></Icon>
<style>
:global(.hes_-lb4x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.4 21.5H4.5v-19h15v9.9m-11-9.9v19m3-14.5h4m-.25 8.25h.01m2.74 0h3.25m-6 2.75h.01M18 18h3.25m-6 2.75h.01m2.74 0h3.25");
}

</style>
