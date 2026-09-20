<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlbnh-bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:monitor-sharp" {...props}></Icon>
<style>
:global(.qlbnh-bao) {
  fill: currentColor;
  d: path("M6 21v-2l1-1H2V3h20v15h-5l1 1v2z");
}

</style>
