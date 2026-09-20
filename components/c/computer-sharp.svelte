<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ieou1ts7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:computer-sharp" {...props}></Icon>
<style>
:global(.ieou1ts7p) {
  fill: currentColor;
  d: path("M1 21v-2h22v2zm1-3V3h20v15z");
}

</style>
