<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpjyso61k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:collapse-content" {...props}></Icon>
<style>
:global(.hpjyso61k) {
  fill: currentColor;
  d: path("M11 13v5h-1v-4H6v-1zm3-7v4h4v1h-5V6z");
}

</style>
