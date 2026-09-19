<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k2dbgxb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:chevrolet" {...props}></Icon>
<style>
:global(.k2dbgxb5g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.389 26.422H30.543v3.114H17.835v-3.114H3.5l1.914-5h12.42v-2.958h12.709v2.958H44.5z");
}

</style>
