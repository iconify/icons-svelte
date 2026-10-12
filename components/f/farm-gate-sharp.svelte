<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf-r4vbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:farm-gate-sharp" {...props}></Icon>
<style>
:global(.lf-r4vbpi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.5H5.5v16.75H2.75zm15.75 0h2.75v16.75H18.5zm-13 3h13m-13 4h13m-13 4h13M5.5 19h13m-13 0l13-11.5");
}

</style>
