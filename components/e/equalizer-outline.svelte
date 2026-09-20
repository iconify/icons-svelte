<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztdk8i0xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:equalizer-outline" {...props}></Icon>
<style>
:global(.ztdk8i0xj) {
  fill: currentColor;
  d: path("M5 19v-5.808h3V19zm5.5 0V5h3v14zm5.5 0V9.808h3V19z");
}

</style>
