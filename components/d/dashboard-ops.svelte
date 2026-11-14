<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkoi_dbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dashboard-ops" {...props}></Icon>
<style>
:global(.kkoi_dbky) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.7 18.5H2.5v-16h16v10.2m-8-10.2v16m-8-8h16m-3 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
