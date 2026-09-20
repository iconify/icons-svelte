<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku0eoab9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-end-square" {...props}></Icon>
<style>
:global(.ku0eoab9h) {
  fill: currentColor;
  d: path("M11 17.5V13H2v-2h9V6.5h11v11z");
}

</style>
