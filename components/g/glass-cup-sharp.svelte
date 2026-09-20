<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymwn462gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:glass-cup-sharp" {...props}></Icon>
<style>
:global(.ymwn462gr) {
  fill: currentColor;
  d: path("M5.2 22L3 2h18l-2.2 20zm1.375-6H17.45l1.3-12H5.25z");
}

</style>
