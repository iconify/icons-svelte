<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u347bkgiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:maintenance-overdue" {...props}></Icon>
<style>
:global(.u347bkgiy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 19.5H2.5v-15h19v15h-.7M2.5 10h19m-14-7.5v4m9-4v4m1.5 8V18m0 3h.01");
}

</style>
