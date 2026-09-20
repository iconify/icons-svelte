<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bhm8fw9hq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-half-fill-12-regular" {...props}></Icon>
<style>
:global(.bhm8fw9hq) {
  fill: currentColor;
  d: path("M2 6a4 4 0 1 1 8 0zm4-5a5 5 0 1 0 0 10A5 5 0 0 0 6 1");
}

</style>
