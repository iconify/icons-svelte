<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzeq_uclt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-landscape-sharp" {...props}></Icon>
<style>
:global(.bzeq_uclt) {
  fill: currentColor;
  d: path("M2 20V4h20v16z");
}

</style>
