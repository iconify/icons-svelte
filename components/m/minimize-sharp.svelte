<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt2fe3thc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:minimize-sharp" {...props}></Icon>
<style>
:global(.qt2fe3thc) {
  fill: currentColor;
  d: path("M6.5 20v-1h11v1z");
}

</style>
