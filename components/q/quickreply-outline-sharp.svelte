<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlsmbdbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:quickreply-outline-sharp" {...props}></Icon>
<style>
:global(.rlsmbdbms) {
  fill: currentColor;
  d: path("M2 22V2h20v8h-2V4H4v13.125L5.15 16H15v2H6zm2-6V4zm15 7v-5h-2v-6h5l-1.7 4h2.2z");
}

</style>
