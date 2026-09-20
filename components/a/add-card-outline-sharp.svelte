<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crjrgdb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:add-card-outline-sharp" {...props}></Icon>
<style>
:global(.crjrgdb2m) {
  fill: currentColor;
  d: path("M2 20V4h20v8H4v6h10v2zM4 8h16V6H4zm15 14v-3h-3v-2h3v-3h2v3h3v2h-3v3zM4 18V6z");
}

</style>
