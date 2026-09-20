<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfd-n5unw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bar-chart" {...props}></Icon>
<style>
:global(.xfd-n5unw) {
  fill: currentColor;
  d: path("M16 19v-4.808h3V19zm-5.5 0V5h3v14zM5 19V9.808h3V19z");
}

</style>
