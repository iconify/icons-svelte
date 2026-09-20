<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5_hg7kll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:60fps-outline-sharp" {...props}></Icon>
<style>
:global(.l5_hg7kll) {
  fill: currentColor;
  d: path("M2 19V5h8v3H5v2h6v9zm3-3h3v-3H5zm10 0h4V8h-4zm-3 3V5h10v14z");
}

</style>
