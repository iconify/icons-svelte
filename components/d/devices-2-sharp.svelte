<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re0sae42q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:devices-2-sharp" {...props}></Icon>
<style>
:global(.re0sae42q) {
  fill: currentColor;
  d: path("M14 20V8h8v12zm4-7.5q.325 0 .538-.225t.212-.525q0-.325-.213-.537T18 11q-.3 0-.525.213t-.225.537q0 .3.225.525T18 12.5M2 20V4h20v2H12v14z");
}

</style>
