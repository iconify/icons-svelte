<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd1_0gbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-horizontal-center-sharp" {...props}></Icon>
<style>
:global(.yd1_0gbkc) {
  fill: currentColor;
  d: path("M11 22v-5H6v-3h5v-4H3V7h8V2h2v5h8v3h-8v4h5v3h-5v5z");
}

</style>
