<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkif7ib3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:inventory-2-sharp" {...props}></Icon>
<style>
:global(.zkif7ib3w) {
  fill: currentColor;
  d: path("M4 21V8.385H3V3h18v5.385h-1V21zM4 7.385h16V4H4zm5.385 5.48h5.23V12h-5.23z");
}

</style>
