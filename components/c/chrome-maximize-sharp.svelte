<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjo_zg3yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chrome-maximize-sharp" {...props}></Icon>
<style>
:global(.fjo_zg3yw) {
  fill: currentColor;
  d: path("M4 20V4h16v16Z");
}

</style>
