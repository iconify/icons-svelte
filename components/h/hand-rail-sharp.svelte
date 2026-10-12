<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm7t4ubqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hand-rail-sharp" {...props}></Icon>
<style>
:global(.vm7t4ubqf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25h4.5v-4.5h4.5v-4.5h4.5v-4.5h5m-14 4v5m4.5-9.5v5m-7.5 2.5l12-12");
}

</style>
